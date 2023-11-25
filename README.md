## Steps to reproduce
- Clone the repo
- Build the container with `docker build . -t clerk-error`
- Run the container with `docker run -p 3000:3000 clerk-error`
- Sign in on the page on http://localhost:3000
- After sign in visit http://localhost:3000/dashboard
- At that step the app crashes only showing an error message
