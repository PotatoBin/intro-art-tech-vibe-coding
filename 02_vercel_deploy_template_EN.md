Deploy this browser-based web game to production using the Vercel CLI.

Use the current project files and workspace context.
Only make changes that are necessary for deployment. Do not change the game concept or major implementation.

Minimum checks before deployment:
- Confirm that the landing page lets visitors play or access the game directly
- Confirm that the artist statement is visible on the landing page
- Confirm that API keys, tokens, passwords, personal information, and `.env` files are not exposed
- Run the build command if one exists, and fix only deployment-blocking issues

Vercel deployment:
- Check whether the Vercel CLI is available
- If it is not installed, install it with the appropriate package manager
- Deploy to production with `vercel --prod`
- If login, project linking, team selection, or environment variables are required, ask clearly for the needed input

After deployment:
- Provide the deployed Vercel URL
- Check that the deployed URL opens correctly
- Check that the game is playable in the deployed environment
- Check that the artist statement is visible
- Briefly summarize any remaining errors or submission risks

Do not claim deployment succeeded unless a Vercel URL is available and verified.
