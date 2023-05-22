#### Support Email Response

[Hello Mr A,
Can you kindly state the change you made to the app so we can try to figure out where the error is coming from.]

---

#### Support Email Troubleshooting steps

[Unhealthy allocation errors  #mean the app could boot okay but couldn’t connect to our health checks.
First of all check to see how your services are configured with fly Services list:
We have a guide to troubleshooting this: https://fly.io/docs/getting-started/troubleshooting/ 
you can check it out
Normally this happens when an app is listening on 127.0.0.1, or an app is listening on a different port than internal_port in the config.]

---

#### Community Forum Response

[Hi Mr A,
Response status code 503 generally means the service is unavailable. This could mean that the server can’t handle the requests because of technical issues.

Try to run fly logs and, after that, fly status.
Sometimes it helps fly to update itself, and it runs.

If you are able to share the logs, it will be much easier to find the issue.]

---

#### Rails App URL

Once you've deployed your Rails app, put the link here: `<app>.fly.dev`
