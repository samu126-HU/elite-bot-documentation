# EliteBot Discord documentation

|      Command      	|                Args                	|                              Description                              	|                                         Notes                                         	|
|:-----------------:	|:----------------------------------:	|:---------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------:	|
|      e.ascii      	|               <text>               	|                      Makes an ascii art for you.                      	|                                 Maximum 24 characters.                                	|
|     e.mkembed     	|          <title> <content>         	|                     Makes an embed by user input.                     	|                           Arg seperators: <a> New line: <n>                           	|
|    e.editembed    	| <msg-id> <new title> <new content> 	|           Edits an embed which is  already made by this bot.          	|          Won't return error messages  if you fuck it up, except syntax error.         	|
|       e.ping      	|               No args              	|                         Check it for yourself.                        	|                First command this bot was able to do, not deleting it.                	|
|    e.checkstock   	|               No args              	|                     Checks current stock values.                      	| Only one time message,  not being updated every 5 minutes. 10 minute global cooldown. 	|
| e.setstockchannel 	|               No args              	| Sets the channel the command was executed in as the  "stock" channel. 	|                                Updated every 5 minutes.                               	|
|   e.remstockmsg   	|               No args              	|                   Removes the current stock message.                  	|                                                                                       	|
|     e.s-accept    	|              <msg-id>              	|               Accepts a suggestion based  on message id.              	|                   Everyone will know the  fact that you accepted it.                  	|
|      e.s-deny     	|              <msg-id>              	|                Denies a suggestion based on message id.               	|                  Everyone will know the the fact that you denied it.                  	|
|      /status      	|           <server status>          	|                        Sets the server status.                        	|                    First arg accepts;  online, offline, debugging.                    	|
