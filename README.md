# AI Thumbnail Generator

Generate YouTube thumbnails instantly using AI. Upload a photo, add context, and get AI-crafted results in both 16:9 and 9:16 aspect ratios.


## Installation

```bash
npm install
```

## Configuration

Copy `.env` file:

```bash
cp env.example .env
```

Set required variables in `.env`:

```env
GEMINI_API_KEY=''

# Required: Demo Credentials (for reviewer access only)
DEMO_USERNAME=''
DEMO_PASSWORD=''

```

## Running

```bash
npm run dev
```

Open http://localhost:5173

## Build

```bash
npm run build
```
