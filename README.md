# disciplinari-agent
Docker compose up, configure open-web-ui pipeline to Disciplinari-agent host (hopefully).

## runs services: open-web-ui, pipelines, ollama, mysql-db and a node.js https server ... maybe that is middleware to a seperate agent server...why, other than cool points seoperating an http server I won't recycle.

## open webui may be a dead end for desire for agent to "bug me, ping me"....need to test
### if open-web-ui bad, try flowise, else react streaming is killer app.
### Goal...it asks user questions....and expects timely repsonses.
### it monitor's time....possibly a magic-number-once per minute batch job that pulls tasks from db...although naked chron job manipulation....curl's the agent server on time is pretty damn light.
### my goals probably, in a config.json at the root of the agent app, will be to crack the whip on me the user towards developing generic coding dev tools/make more cooler stuff/self expand.
#### config.json
### db for chat history, redundency check on if chron job executed....
### near term RAG integration...ugh...or flowise agent integration
