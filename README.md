# Backgammon Detection - Vercel Frontend

This is the frontend application for backgammon piece detection.

## Setup

1. Update API URL in `index.html`:
   - Find line: `const API_URL = 'https://192.168.100.40:5000/detect';`
   - Replace with your Render.com API URL: `const API_URL = 'https://your-app.onrender.com/detect';`

2. Deploy to Vercel:
   ```bash
   cd deploy_vercel
   vercel deploy
   ```

## Configuration

Make sure to update the API URL after deploying the backend to Render.com
