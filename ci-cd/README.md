**Here's a challenge for you!**

We are actively looking for builders to join the IT team to improve our CI/CD pipelines. This challenge is an assessment of your expertise in the field.

Once you are done please share the GitHub url with us at challenge@flinks.io 

Have fun!


Requirements:
1. Build a simple hello world app (C#, Go, Java or Python)
   * /hello endpoint returning a json response and HTTP 200 code
   * Create a GitHub repo for the project
2. Setup a release branch
3. Build a container hosting your app
   * We don't want any source code in the container
   * It must build anywhere as long as Docker is installed
   * The final image must be as small as possible
4. Create a test suite that will assert HTTP 200 on the /hello endpoint to be used in CI/CD 
5. Document the proposed SDLC (branchess, testing, deployment) for this project in a readme file

Bonus points:
   * The app supports CRUD operations
   * TravisCI (or equivalent) integration in the GitHub repo
   * Code review integration in the process
   * Security review integrated in the process

