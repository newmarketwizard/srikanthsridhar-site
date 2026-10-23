# Srikanth Sridhar — Personal Portfolio

Portfolio website showcasing technology and transformation leadership across AI strategy, enterprise architecture, autonomous MCP frameworks, and agentic workflows.

## Project Structure

```
├── .firebaserc       # Firebase project binding
├── firebase.json     # Firebase Hosting configuration
├── public/           # Static assets & web root
│   ├── index.html    # Main portfolio page
│   └── 404.html      # 404 error page
└── .github/          # GitHub Actions workflows for continuous deployment
```

## Local Development & Preview

You can preview the site locally using any static web server or Firebase CLI:

```bash
# Using Python
python3 -m http.server --directory public 8000

# Using Firebase CLI
npx firebase-tools serve --only hosting
```

## Deployment

Deployments to Firebase Hosting are automated via GitHub Actions on push to `main`.

To deploy manually via CLI:
```bash
npx firebase-tools deploy --only hosting
```
