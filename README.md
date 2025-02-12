# disciplinari-agent
Docker compose up, configure open-web-ui pipeline to Disciplinari-agent host (hopefully).

## runs services: 
- ollama,
- mysql-db/possibly qdrant instead 
- node-alpine? https server on top of a an os with curl and chronjob handy.
- react streaming front end

  

## Goal...it asks user questions....and expects timely repsonses, in addition to normal back and forth. 
### possible "gamification" for user to get "Obedience High Score"
### "Punish" user to prevent user from just saying f' it...no ideas. High Score might include a dollar jar or debt of deserved "reward".
### Immediate goal is to focus on "Lets code for 3 hours, and by the end I want to have spent the last 15 minutes just reviewing tests and hands on user use case use case testing...."
### lol...24 hour life coach application will likely be usage choices away and sounds like a living hell.



### it monitor's time....possibly a magic-number-once per minute batch job that pulls tasks from db...although naked chron job manipulation....curl's the agent server on time is pretty damn light.
### my goals probably, in a config.json at the root of the agent app, will be to crack the whip on me the user towards developing generic coding dev tools/make more cooler stuff/self expand.
#### config.json
### db for chat history, redundency check on if chron job executed....
#### TODO is manage db for local back up
#### almost want mongodb for on the fly agent work/wtf schema , while
#### adding qdrant for rag feels need, so mongo is a bit ott phase 1.
#### - explore qdrant for chat history and mongo equiv OVER sql whatever
#### - near term RAG integration...ugh...or flowise agent integration
