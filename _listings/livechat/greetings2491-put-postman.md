{
  "info": {
    "name": "LiveChat Update greeting",
    "_postman_id": "b645f18b-79ce-45be-a96e-96cbb8e215c5",
    "description": "Use this request to change the name or message of a greeting.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Webhook",
      "item": [
        {
          "id": "3a2f30ad-30b9-4db4-807d-172a4183401a",
          "name": "Webhooks12345Delete",
          "request": {
            "url": "http://api.livechatinc.com/webhooks/12345",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a webhook with the given ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e217779-2799-415c-935f-373eb045ca2d"
            }
          ]
        }
      ]
    },
    {
      "name": "Chat",
      "item": [
        {
          "id": "f0c58f03-81c8-4d20-811c-63a948fc73e7",
          "name": "ReportsChatsRatingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/ratings?date_from=%7B%7D&date_to=%7B%7D&group=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how many chats have been rated and how they have been rated during a specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee7f58c6-2296-44a0-b042-ff8bb27d04ea"
            }
          ]
        },
        {
          "id": "092284ac-fe48-4e35-a678-07ef9a55803f",
          "name": "ReportsChatsEngagementGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/engagement?agent=%7B%7D&date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This report shows you where you get your chats from. They can come from i.e. automatic invitations, manual invitations or the visitors can start the chats by themselves."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30611f8d-2eb0-43a6-8245-d7e34312ac07"
            }
          ]
        },
        {
          "id": "641d2113-039a-4e8f-b485-caa7543096e3",
          "name": "ReportsChatsRatingsRankingGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/ratings/ranking",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the ratio of good to bad ratings for each operator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa1e1b98-8a61-4410-b15f-c928a45c7f71"
            }
          ]
        },
        {
          "id": "3e45d65f-57df-46b4-8531-2a79ab5c4ece",
          "name": "ChatsABC123TagsPut",
          "request": {
            "url": "http://api.livechatinc.com/chats/ABC123/tags",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tag[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "tag[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "This method updates the tags assigned to a chat."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab89b6c3-fd4f-4e7f-b9d6-96508416e270"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "79feb729-6f05-49a8-8bd4-82e4959152ae",
          "name": "CannedResponsesABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of all currently set canned responses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef2889f9-8d5f-4256-be6d-120006be2a6c"
            }
          ]
        },
        {
          "id": "a8d7c859-a284-4be8-9f68-ee5922f53a95",
          "name": "GreetingsGet",
          "request": {
            "url": "http://api.livechatinc.com/greetings?groups=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of all greetings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8f87de1-16f7-4f24-90e0-d4907f83faff"
            }
          ]
        },
        {
          "id": "91f6e70e-2df3-4c8c-a28a-061b8f1736e9",
          "name": "TagsGet",
          "request": {
            "url": "http://api.livechatinc.com/tags?group=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns tags from all groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "765fdfab-09e6-471a-95dd-f6e563393fb4"
            }
          ]
        },
        {
          "id": "b6026011-9cbd-4bc4-b34a-a22dfc9f2803",
          "name": "TicketsGet",
          "request": {
            "url": "http://api.livechatinc.com/tickets?date_from=%7B%7D&status=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all tickets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "414689dc-8d58-4d48-8f70-355a91d39d79"
            }
          ]
        },
        {
          "id": "6bd56953-e375-4eec-b338-4a8b4d610b2e",
          "name": "CannedResponsesGet",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of all currently set canned responses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3eab2fa9-802e-48a3-9f61-665270ccbed6"
            }
          ]
        },
        {
          "id": "e3aaefe2-0084-478f-bffc-18b548a8f0a7",
          "name": "GroupsGet",
          "request": {
            "url": "http://api.livechatinc.com/groups",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all created groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5dced4e8-7f5a-4ce7-a81b-b6ff4826ab06"
            }
          ]
        },
        {
          "id": "df873265-0878-4835-83ef-ab31b14c7009",
          "name": "GoalsGet",
          "request": {
            "url": "http://api.livechatinc.com/goals",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all currently set goals. The active parameter indicates whether a goal is enabled or not."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10aee50b-e9ad-43a1-83fd-608b75f6461a"
            }
          ]
        },
        {
          "id": "e45b5a54-426f-4149-9014-e18bfd1847b6",
          "name": "ChatsGet",
          "request": {
            "url": "http://api.livechatinc.com/chats",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all ended chats."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc3aa2d6-5d4b-4184-8674-cc83bd927508"
            }
          ]
        },
        {
          "id": "9daa1f4c-9bea-4a14-80bd-fb439ab82f03",
          "name": "AgentsGet",
          "request": {
            "url": "http://api.livechatinc.com/agents",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all LiveChat agents list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d421be2-fbd3-476c-accb-8611d94961b8"
            }
          ]
        },
        {
          "id": "882ef850-2a78-435f-a05b-491be3c932aa",
          "name": "VisitorsGet",
          "request": {
            "url": "http://api.livechatinc.com/visitors?group=%5B%7B%7D%5D&state=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of the visitors on the pages with the tracking code installed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1219757-f1ea-4fd1-9178-44b47db91751"
            }
          ]
        }
      ]
    },
    {
      "name": "Canned",
      "item": [
        {
          "id": "916c3bd2-70fa-4941-968c-a6abcf8287e0",
          "name": "CannedResponsesABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tags[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates the specified canned response by setting the values of the parameters passed. Any parameters not provided will be left unchanged."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "556baad0-fabd-45ab-8164-3bcfec5b59e2"
            }
          ]
        }
      ]
    },
    {
      "name": "Remove",
      "item": [
        {
          "id": "3b292106-5b16-4d92-bba0-d0e1c580d516",
          "name": "CannedResponsesABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a canned response with the given CANNED_RESPONSE_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dffea010-b30d-4c56-a600-e4f506ee87f3"
            }
          ]
        },
        {
          "id": "0cbf9d85-d346-46c0-a662-c96c66882e0e",
          "name": "GroupsABC123Delete2",
          "request": {
            "url": "http://api.livechatinc.com/groups/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a group with the given GROUP_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e054cfee-0ad4-4bb7-bf05-69deb3e25aa1"
            }
          ]
        },
        {
          "id": "dc50ab43-0c00-49c5-9a81-5d77d8056a38",
          "name": "AgentsJohnPublicComDelete",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes an agent."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c8fcec8-a18d-4411-ad1b-f75ddf064550"
            }
          ]
        },
        {
          "id": "c59f6fdc-9659-4f45-8539-aef718a81ae3",
          "name": "GreetingsABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/greetings/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4002b47a-7e03-4dd1-800f-b083a670c042"
            }
          ]
        },
        {
          "id": "53214a0c-6329-43d1-82fb-6b033e2ca5b7",
          "name": "GoalsABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a goal with the given GOAL_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39b8790f-ae97-48a1-9d38-1bd2c1ae3b2b"
            }
          ]
        }
      ]
    },
    {
      "name": "Group",
      "item": [
        {
          "id": "ef516c8d-afb0-4d63-b003-5f13d94eaffa",
          "name": "GroupsABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/groups/ABC123",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "agents[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "agents[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates the specified group by setting the values of the parameters passed. Any parameters not provided will be left unchanged."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31e65f31-d352-471e-b79f-e4d8fad7b6f5"
            }
          ]
        }
      ]
    },
    {
      "name": "New",
      "item": [
        {
          "id": "f539fda0-b0eb-43b6-89df-124a5f7792b9",
          "name": "GreetingsPost",
          "request": {
            "url": "http://api.livechatinc.com/greetings",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][operator]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][type]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][value]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][operator]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][type]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][value]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Use this function to create a new greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abeb7245-1b46-4250-9f8a-76ac7c2e71e6"
            }
          ]
        },
        {
          "id": "9ea5f2c0-bba5-4428-b697-c341325083af",
          "name": "WebhooksPost",
          "request": {
            "url": "http://api.livechatinc.com/webhooks",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "data_types",
                  "value": "[{}]",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "event_type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new webhook."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "305c2ffe-2f8e-44b4-a711-fc1171230a3b"
            }
          ]
        },
        {
          "id": "19bf865c-b679-4d91-8caa-547e63aa081b",
          "name": "CannedResponsesPost",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tags[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "tags[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new canned response."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c4a6a13-3867-4ecb-809c-c0d79d003dbc"
            }
          ]
        },
        {
          "id": "2339a00c-f4d7-4f22-9b76-bc75a432f827",
          "name": "GroupsPost",
          "request": {
            "url": "http://api.livechatinc.com/groups",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "agents[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "agents[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new group in your license."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbc0ff19-14e9-4d8f-8c35-da0b229d2b14"
            }
          ]
        },
        {
          "id": "052ce593-ba33-4d55-841b-b8775a1bcffe",
          "name": "GoalsPost",
          "request": {
            "url": "http://api.livechatinc.com/goals",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "match_type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new goal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f77ffb58-fe03-4240-b9a8-b14b587f05e9"
            }
          ]
        },
        {
          "id": "4a6f361e-8b59-4fd8-bbb5-a57d3aeeb40f",
          "name": "AgentsPost",
          "request": {
            "url": "http://api.livechatinc.com/agents",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "login",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new agent in your license."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d38c4b4b-d403-43d3-920f-16bc399e8bda"
            }
          ]
        }
      ]
    },
    {
      "name": "Display",
      "item": [
        {
          "id": "465b1dde-7fc9-4baa-8300-e98b9364b44d",
          "name": "WebhooksGet",
          "request": {
            "url": "http://api.livechatinc.com/webhooks",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of webhooks that have been created in a LiveChat account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75a7577c-bebb-4681-9687-160036992aa7"
            }
          ]
        }
      ]
    },
    {
      "name": "Greetings",
      "item": [
        {
          "id": "47bde643-fb99-4bc7-ad53-44d3edf188d5",
          "name": "ReportsChatsGreetingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/greetings?date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the “greetings to chats to goals” conversion rates report.\n\ndisplayed is the number of displayed greetings. accepted tells you how many chats resulted from these greetings. goals tells you how many goals resulted from these greetings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b003923-f329-4f70-8004-85712ae7f49b"
            }
          ]
        }
      ]
    },
    {
      "name": "Tag",
      "item": [
        {
          "id": "948c224d-dbd4-4d7b-b75e-0fdb2f9de01b",
          "name": "TagsPost",
          "request": {
            "url": "http://api.livechatinc.com/tags",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "author",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "group",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "tag",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Adds a new tag. Note that only the owner and the admins are authorized to use this."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbe5e6c7-1793-450b-8e1a-d61ef102a721"
            }
          ]
        },
        {
          "id": "a2dfa0a4-c450-4243-b4c3-b2d29b21c8f3",
          "name": "TagsSupportDelete",
          "request": {
            "url": "http://api.livechatinc.com/tags/support",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "group",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Deletes a tag from the chosen group. The agents will no longer be able to tag chats and tickets using this tag.\n\nDeleting a tag will not remove it from the archived chats and tickets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a34ba922-dd73-4d84-85a3-8031d7917cbe"
            }
          ]
        }
      ]
    },
    {
      "name": "Single",
      "item": [
        {
          "id": "05a49481-bd31-4d98-91c7-2ba6705b1f9b",
          "name": "AgentsJohnPublicComGet",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns complete details of the agent for the given LOGIN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db99c01f-ec1e-47f1-9a03-4d16d9449839"
            }
          ]
        },
        {
          "id": "2940f057-17bb-4743-b129-57ccfdfc0dfe",
          "name": "AgentsJohnPublicComPut",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "job_title",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Returns complete details of the agent for the given LOGIN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a746d83d-20b7-40a5-b9e3-cbaf040ce649"
            }
          ]
        },
        {
          "id": "543cab1c-cfc1-4244-bacc-52f360720e24",
          "name": "ChatsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/chats/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single chat item for the given CHAT_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d685c35-7c22-49d5-a9de-bcc3cc6e5366"
            }
          ]
        },
        {
          "id": "e813a30f-3875-4429-92e3-f4f140f61cfc",
          "name": "GreetingsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/greetings/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the specified greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c1cdd51-cc45-4598-8670-bfe5822c120c"
            }
          ]
        },
        {
          "id": "fb912112-90b9-4f8f-95e7-29e4a40f9964",
          "name": "GroupsByGroupIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.livechatinc.com",
              "path": [
                "groups/:group_id"
              ],
              "variable": [
                {
                  "id": "group_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns group details for the given GROUP_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb83df21-e60e-4ac5-becc-18c423a77611"
            }
          ]
        },
        {
          "id": "5dd9749c-e5bc-4219-a893-1289481ba9a3",
          "name": "GoalsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the goal details for the given GOAL_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de9e5ce8-d8c4-4f77-a428-316eda21b3d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Ticket",
      "item": [
        {
          "id": "48bfd175-ca3c-4843-8dcc-73f3f5a1a97b",
          "name": "TicketsPost",
          "request": {
            "url": "http://api.livechatinc.com/tickets",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "message",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requester[mail]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requester[name]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "subject",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new ticket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "078db4b0-d59d-48ad-b774-dc7dfdf49d14"
            }
          ]
        },
        {
          "id": "b833d417-fcd0-4fdb-8260-38d52ba1a355",
          "name": "ReportsTicketsTicketSourcesGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/ticket_sources?date_from=%7B%7D&date_to=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the distribution of the tickets between various channels."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28a74cf1-c4e7-4520-b2da-fbf82c740db1"
            }
          ]
        },
        {
          "id": "fcf364d6-0725-4559-98c9-52fb1b82a169",
          "name": "ReportsTicketsRatingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/ratings?date_from=%7B%7D&date_to=%7B%7D&group=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the tickets that were rated during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e3a3fc0-b529-4b0b-92b3-f7ef0f62c9fc"
            }
          ]
        },
        {
          "id": "2538bbeb-80ab-4228-97bc-e9c94ec75cef",
          "name": "Tickets5FUEDTagsPut",
          "request": {
            "url": "http://api.livechatinc.com/tickets/5FUED/tags",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tag",
                  "value": "[{}]",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates tags associated with the ticket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a313b572-258a-45fd-9a79-3a20a244d712"
            }
          ]
        },
        {
          "id": "5b6e2c61-4b38-49e9-aa70-342b46f1f567",
          "name": "ReportsTicketsRatingsRankingGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/ratings/ranking",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the ratio of good to bad ratings for each operator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d5be717-ff2c-4f91-bfba-cf2d473ddfa6"
            }
          ]
        }
      ]
    },
    {
      "name": "Solved",
      "item": [
        {
          "id": "c3cde3bf-caf9-4b14-a67f-5eb4dded119c",
          "name": "ReportsTicketsSolvedTicketsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/solved_tickets?date_from=%7B%7D&date_to=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the number of the tickets solved during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0f94368-5c72-46d2-95f7-97755956860a"
            }
          ]
        }
      ]
    },
    {
      "name": "Chats",
      "item": [
        {
          "id": "2465666f-912f-4904-a61e-2eb8ab399c63",
          "name": "ReportsChatsFirstResponseTimeGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/first_response_time",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The average amount of time it takes the agents to respond to a new chat over a specified period of time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "773c192a-fe71-4776-ab92-1ce63e28684f"
            }
          ]
        },
        {
          "id": "d13d76df-a619-4257-af2b-831527c53552",
          "name": "ReportsChatsResponseTimeGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/response_time",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The average amount of time it takes the agents to respond to a new message in a chat during a specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0094072-c572-4ec7-b6f1-f1a920cfa275"
            }
          ]
        }
      ]
    },
    {
      "name": "Total",
      "item": [
        {
          "id": "d57ba1ff-f734-4f25-b615-e6ad0584addc",
          "name": "ReportsChatsTotalChatsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/total_chats?agent=%7B%7D&date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how many chats occurred during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71cbf02f-93a0-4be0-b333-dbd7926bfcc3"
            }
          ]
        }
      ]
    },
    {
      "name": "Goal",
      "item": [
        {
          "id": "4b39120b-19e9-4c58-b912-924f0e67e1af",
          "name": "GoalsABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "active",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates the specified goal by setting the values of the parameters passed. Any parameters not provided will be left unchanged.\n\nThe GOAL_ID is obtained from the goals list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc4da430-6509-4f8e-8f1b-8e6f531928e4"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability",
      "item": [
        {
          "id": "dc16f075-80b3-488e-9b65-8ac005b4101c",
          "name": "ReportsAvailabilityGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/availability",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how long an agent (or a group or the whole account) was available for chatting during a specified period. When querying for one day, the results are shown in minutes per every hour, otherwise in hours for each day."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34da2c4b-1510-4a7e-bd89-e1701311c114"
            }
          ]
        }
      ]
    },
    {
      "name": "Tickets",
      "item": [
        {
          "id": "10ad0086-cc2b-41ab-9e51-6acf048e8c5b",
          "name": "ReportsTicketsResolutionTimeGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/resolution_time?date_from=%7B%7D&date_to=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the resolution time of the tickets that were solved during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6e2dce7b-526b-405b-b448-7a6ff3cd646e"
            }
          ]
        }
      ]
    },
    {
      "name": "Goals",
      "item": [
        {
          "id": "de8de1d0-38b3-47aa-8c1d-45c8bf3bfda4",
          "name": "ReportsChatsGoalsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/goals?date_from=%7B%7D&goal=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the number of reached goals."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "255a4b4d-693f-4a8b-99aa-1f47969d88f8"
            }
          ]
        }
      ]
    },
    {
      "name": "Queued",
      "item": [
        {
          "id": "99f2901a-5e35-4101-b928-491061bb4e85",
          "name": "ReportsChatsQueuedVisitorsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/queued_visitors?date_from=%7B%7D&group=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how many visitors waited in the queue and how many abandoned the queue or proceeded to chats"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6fa0490-c80d-4f24-ace1-e6ecfa90a228"
            }
          ]
        }
      ]
    },
    {
      "name": "Queue",
      "item": [
        {
          "id": "1243b554-e432-449a-82de-d021ba35b634",
          "name": "ReportsChatsQueuedVisitorsWaitingTimesGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/queued_visitors/waiting_times?date_from=%7B%7D&group=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the Minimum, Average and Maximum waiting time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c25a066-0737-4b60-93c7-fc2ff6c5ab5e"
            }
          ]
        }
      ]
    },
    {
      "name": "Chatting",
      "item": [
        {
          "id": "5f6da023-2a77-47d4-b94a-dc29a334cd4f",
          "name": "ReportsChatsChattingTimeGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/chatting_time",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how much time an agent (or a group) spent on chatting during a specified period. When querying for one day, the results are shown in minutes per every hour, otherwise in hours for each day."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30ec1aa9-5978-4576-bcb8-60baf756d8c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Mark",
      "item": [
        {
          "id": "77cbf21b-390a-4ddb-b948-06344a205e19",
          "name": "GoalsABC123MarkAsSuccessfulPost",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123/mark_as_successful",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "visitor_id",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "The GOAL_ID is obtained from the goals list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f7d1dd7-6a21-4c33-8a04-91c781043459"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "fe584f8a-d01f-4ff8-9805-0c8448d8e24b",
          "name": "StatusGet",
          "request": {
            "url": "http://api.livechatinc.com/status",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the current LiveChat status. Available return values: online, offline."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "718fbd38-07e3-4d7e-abaa-4d4ad6ceb224"
            }
          ]
        }
      ]
    },
    {
      "name": "Greeting",
      "item": [
        {
          "id": "718330bf-51a4-4c22-b674-b1b75b5d68f2",
          "name": "Greetings2491Put",
          "request": {
            "url": "http://api.livechatinc.com/greetings/2491",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "properties[greeting-message_text]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Use this request to change the name or message of a greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40ecd0eb-f3b5-4a8b-a8a1-33bcd87c71c6"
            }
          ]
        }
      ]
    }
  ]
}