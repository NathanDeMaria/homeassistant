Things I forgot on setup last time:

Before your first `docker-compose up -d`:
- Get your router to port forward 8123, 80, and 443

# Manual Things

- To be able to run Google Assistant commands from scripts (ex: I want to trigger something via IFTT through a webhook), add the [Google Assistant SDK](https://www.home-assistant.io/integrations/google_assistant_sdk)
- Learn remote commands with the tool at `/config/developer-tools/action`
    - Target: entity -> IR blaster
    - Device: pick a name
    - Command: pick a name
    - Click "Perform action", then hit the button on your remote
    - Check out the file `./config/.storage/<somewhere>_codes` to see them get added.
