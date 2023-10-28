# 👩‍🎨 Scripted Snapshots

Modify images by chatting with a generative AI model.



## How it works

This app is powered by:

🚀 [Replicate](https://replicate.com), a platform for running machine learning models in the cloud.

🎨 [InstructPix2Pix](https://replicate.com/timothybrooks/instruct-pix2pix), an open-source machine learning model that generates images from text.



⚡️ Next.js [server-side API routes](pages/api), for talking to the Replicate API.

👀 Next.js React components, for the browser UI.

🍃 [Tailwind CSS](https://tailwindcss.com/), for styles.


## Development

1. Install a recent version of [Node.js](https://nodejs.org/)
1. Copy your [Replicate API token](https://replicate.com) and set it in your environment:
    ```
    echo "REPLICATE_API_TOKEN=<your-token-here>" > .env.local
    ````
1. Install dependencies and run the server:
    ```
    npm install
    npm run dev
    ```
1. Open [localhost:3000](http://localhost:3000) in your browser. That's it!
