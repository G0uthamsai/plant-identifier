# Plant Identifier Next.js 14 App

## Setup

1. Create a `.env.local` file in the project root with the following content:

```
GOOGLE_GEMINI_API_KEY=your_google_gemini_api_key_here
```

Replace `your_google_gemini_api_key_here` with your actual Google Gemini API key.

2. Install dependencies:

```
npm install
```

3. Run the development server:

```
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- Upload a plant image on the main page.
- Click "Identify Plant" to send the image to the Google Gemini API.
- The plant name and description will be displayed after identification.

## Notes

- Ensure your API key has the necessary permissions for the Google Gemini Plant Identifier API.
- The API route `/api/identify-plant` handles the image upload and calls the Google Gemini API.

## Testing

Please test the following critical paths:

- Image upload and identification
- Loading and error states
- Display of plant information

You can perform critical-path testing or thorough testing as needed.
