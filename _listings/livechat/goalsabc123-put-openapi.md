---
swagger: "2.0"
x-collection-name: LiveChat
x-complete: 0
info:
  title: LiveChat Update a goal
  description: |-
    Updates the specified goal by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

    The GOAL_ID is obtained from the goals list.
  version: 1.0.0
host: api.livechatinc.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks/12345:
    delete:
      summary: Delete a webhook
      description: Deletes a webhook with the given ID.
      operationId: Webhooks12345Delete
      x-api-path-slug: webhooks12345-delete
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Webhook
  /reports/chats/ratings:
    get:
      summary: Chat ratings report
      description: Shows how many chats have been rated and how they have been rated
        during a specified period.
      operationId: ReportsChatsRatingsGet
      x-api-path-slug: reportschatsratings-get
      parameters:
      - in: query
        name: date_from
      - in: query
        name: date_to
      - in: query
        name: group
      - in: query
        name: group_by
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Ratings
      - Report
  /canned_responses/ABC123:
    get:
      summary: List all canned responses1
      description: Returns the list of all currently set canned responses.
      operationId: CannedResponsesABC123Get
      x-api-path-slug: canned-responsesabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Canned
      - Responses1
    put:
      summary: Update a canned response
      description: Updates the specified canned response by setting the values of
        the parameters passed. Any parameters not provided will be left unchanged.
      operationId: CannedResponsesABC123Put
      x-api-path-slug: canned-responsesabc123-put
      parameters:
      - in: formData
        name: tags[0]
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Canned
      - Response
    delete:
      summary: Remove a canned response
      description: Removes a canned response with the given CANNED_RESPONSE_ID.
      operationId: CannedResponsesABC123Delete
      x-api-path-slug: canned-responsesabc123-delete
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Canned
      - Response
  /groups/ABC123:
    put:
      summary: Update a group
      description: Updates the specified group by setting the values of the parameters
        passed. Any parameters not provided will be left unchanged.
      operationId: GroupsABC123Put
      x-api-path-slug: groupsabc123-put
      parameters:
      - in: formData
        name: agents[0]
      - in: formData
        name: agents[1]
      - in: formData
        name: name
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Group
    delete:
      summary: Remove a group
      description: Removes a group with the given GROUP_ID.
      operationId: GroupsABC123Delete2
      x-api-path-slug: groupsabc123-delete
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Group
  /reports/chats/engagement:
    get:
      summary: Chat engagement
      description: This report shows you where you get your chats from. They can come
        from i.e. automatic invitations, manual invitations or the visitors can start
        the chats by themselves.
      operationId: ReportsChatsEngagementGet
      x-api-path-slug: reportschatsengagement-get
      parameters:
      - in: query
        name: agent
      - in: query
        name: date_from
      - in: query
        name: date_to
      - in: query
        name: group_by
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Engagement
  /greetings:
    get:
      summary: List all greetings
      description: Returns the list of all greetings.
      operationId: GreetingsGet
      x-api-path-slug: greetings-get
      parameters:
      - in: query
        name: groups
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Greetings
    post:
      summary: Create a new greeting
      description: Use this function to create a new greeting.
      operationId: GreetingsPost
      x-api-path-slug: greetings-post
      parameters:
      - in: formData
        name: name
      - in: formData
        name: rules[0][operator]
      - in: formData
        name: rules[0][type]
      - in: formData
        name: rules[0][value]
      - in: formData
        name: rules[1][operator]
      - in: formData
        name: rules[1][type]
      - in: formData
        name: rules[1][value]
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - New
      - Greeting
  /webhooks:
    get:
      summary: Display configured webhooks
      description: Returns a list of webhooks that have been created in a LiveChat
        account.
      operationId: WebhooksGet
      x-api-path-slug: webhooks-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Display
      - Configured
      - Webhooks
    post:
      summary: Create a new webhook
      description: Creates a new webhook.
      operationId: WebhooksPost
      x-api-path-slug: webhooks-post
      parameters:
      - in: formData
        name: data_types[]
      - in: formData
        name: event_type
      - in: formData
        name: url
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - New
      - Webhook
  /reports/chats/greetings:
    get:
      summary: Greetings
      description: "Returns the \u201Cgreetings to chats to goals\u201D conversion
        rates report.\n\ndisplayed is the number of displayed greetings. accepted
        tells you how many chats resulted from these greetings. goals tells you how
        many goals resulted from these greetings."
      operationId: ReportsChatsGreetingsGet
      x-api-path-slug: reportschatsgreetings-get
      parameters:
      - in: query
        name: date_from
      - in: query
        name: date_to
      - in: query
        name: group_by
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Greetings
  /tags:
    get:
      summary: List all tags
      description: Returns tags from all groups.
      operationId: TagsGet
      x-api-path-slug: tags-get
      parameters:
      - in: query
        name: group
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Tags
    post:
      summary: Add a tag
      description: Adds a new tag. Note that only the owner and the admins are authorized
        to use this.
      operationId: TagsPost
      x-api-path-slug: tags-post
      parameters:
      - in: formData
        name: author
      - in: formData
        name: group
      - in: formData
        name: tag
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Tag
  /agents/john@public.com:
    get:
      summary: Get a single agent details
      description: Returns complete details of the agent for the given LOGIN.
      operationId: AgentsJohnPublicComGet
      x-api-path-slug: agentsjohnpublic-com-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Agent
      - Details
    put:
      summary: Get a single agent details
      description: Returns complete details of the agent for the given LOGIN.
      operationId: AgentsJohnPublicComPut
      x-api-path-slug: agentsjohnpublic-com-put
      parameters:
      - in: formData
        name: job_title
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Agent
      - Details
    delete:
      summary: Remove an agent
      description: Removes an agent.
      operationId: AgentsJohnPublicComDelete
      x-api-path-slug: agentsjohnpublic-com-delete
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Agent
  /tickets:
    get:
      summary: Get list of tickets
      description: Returns all tickets.
      operationId: TicketsGet
      x-api-path-slug: tickets-get
      parameters:
      - in: query
        name: date_from
      - in: query
        name: status
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Tickets
    post:
      summary: Create a ticket
      description: Creates a new ticket.
      operationId: TicketsPost
      x-api-path-slug: tickets-post
      parameters:
      - in: formData
        name: message
      - in: formData
        name: requester[mail]
      - in: formData
        name: requester[name]
      - in: formData
        name: subject
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Ticket
  /reports/tickets/solved_tickets:
    get:
      summary: Solved tickets
      description: Shows the number of the tickets solved during the specified period.
      operationId: ReportsTicketsSolvedTicketsGet
      x-api-path-slug: reportsticketssolved-tickets-get
      parameters:
      - in: query
        name: date_from
      - in: query
        name: date_to
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Solved
      - Tickets
  /reports/chats/first_response_time:
    get:
      summary: Chats first response time
      description: The average amount of time it takes the agents to respond to a
        new chat over a specified period of time.
      operationId: ReportsChatsFirstResponseTimeGet
      x-api-path-slug: reportschatsfirst-response-time-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Chats
      - First
      - Response
      - Time
  /canned_responses:
    get:
      summary: List all canned responses
      description: Returns the list of all currently set canned responses.
      operationId: CannedResponsesGet
      x-api-path-slug: canned-responses-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Canned
      - Responses
    post:
      summary: Create a new canned response
      description: Creates a new canned response.
      operationId: CannedResponsesPost
      x-api-path-slug: canned-responses-post
      parameters:
      - in: formData
        name: tags[0]
      - in: formData
        name: tags[1]
      - in: formData
        name: text
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - New
      - Canned
      - Response
  /reports/chats/ratings/ranking:
    get:
      summary: Chat Ranking
      description: Shows the ratio of good to bad ratings for each operator.
      operationId: ReportsChatsRatingsRankingGet
      x-api-path-slug: reportschatsratingsranking-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Ranking
  /groups:
    get:
      summary: List all groups
      description: Returns all created groups.
      operationId: GroupsGet
      x-api-path-slug: groups-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Groups
    post:
      summary: Create a new group
      description: Creates a new group in your license.
      operationId: GroupsPost
      x-api-path-slug: groups-post
      parameters:
      - in: formData
        name: agents[0]
      - in: formData
        name: agents[1]
      - in: formData
        name: name
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - New
      - Group
  /chats/ABC123:
    get:
      summary: Get single chat
      description: Returns a single chat item for the given CHAT_ID.
      operationId: ChatsABC123Get
      x-api-path-slug: chatsabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Chat
  /reports/tickets/ticket_sources:
    get:
      summary: Ticket sources
      description: Shows the distribution of the tickets between various channels.
      operationId: ReportsTicketsTicketSourcesGet
      x-api-path-slug: reportsticketsticket-sources-get
      parameters:
      - in: query
        name: date_from
      - in: query
        name: date_to
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Ticket
      - Sources
  /greetings/ABC123:
    get:
      summary: Get a single greeting
      description: Returns the specified greeting.
      operationId: GreetingsABC123Get
      x-api-path-slug: greetingsabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Greeting
    delete:
      summary: Remove a greeting
      description: Removes a greeting.
      operationId: GreetingsABC123Delete
      x-api-path-slug: greetingsabc123-delete
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Greeting
  /groups/{group_id}:
    get:
      summary: Get a single group details
      description: Returns group details for the given GROUP_ID.
      operationId: GroupsByGroupIdGet
      x-api-path-slug: groupsgroup-id-get
      parameters:
      - in: path
        name: group_id
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Group
      - Details
  /reports/chats/total_chats:
    get:
      summary: Total chats
      description: Shows how many chats occurred during the specified period.
      operationId: ReportsChatsTotalChatsGet
      x-api-path-slug: reportschatstotal-chats-get
      parameters:
      - in: query
        name: agent
      - in: query
        name: date_from
      - in: query
        name: date_to
      - in: query
        name: group_by
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Total
      - Chats
  /goals:
    get:
      summary: List all goals
      description: Returns all currently set goals. The active parameter indicates
        whether a goal is enabled or not.
      operationId: GoalsGet
      x-api-path-slug: goals-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Goals
    post:
      summary: Add a new goal
      description: Creates a new goal.
      operationId: GoalsPost
      x-api-path-slug: goals-post
      parameters:
      - in: formData
        name: match_type
      - in: formData
        name: name
      - in: formData
        name: type
      - in: formData
        name: url
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - New
      - Goal
  /chats:
    get:
      summary: Get list of chats
      description: Returns all ended chats.
      operationId: ChatsGet
      x-api-path-slug: chats-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Chats
  /agents:
    get:
      summary: List all agents
      description: Returns all LiveChat agents list
      operationId: AgentsGet
      x-api-path-slug: agents-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Agents
    post:
      summary: Create a new agent
      description: Creates a new agent in your license.
      operationId: AgentsPost
      x-api-path-slug: agents-post
      parameters:
      - in: formData
        name: login
      - in: formData
        name: name
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - New
      - Agent
  /goals/ABC123:
    get:
      summary: Get a single goal details
      description: Returns the goal details for the given GOAL_ID.
      operationId: GoalsABC123Get
      x-api-path-slug: goalsabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Goal
      - Details
    put:
      summary: Update a goal
      description: |-
        Updates the specified goal by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

        The GOAL_ID is obtained from the goals list.
      operationId: GoalsABC123Put
      x-api-path-slug: goalsabc123-put
      parameters:
      - in: formData
        name: active
      - in: formData
        name: name
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Goal
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---