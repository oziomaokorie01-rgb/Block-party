# Block-party
Transforming on-chain activity into music.Block Party is a generative, reactive lo-fi orchestra that translates real-time on-chain activity on the Somnia Network into a living musical and visual experience.
Developed by Senseii_ciel, this project was built for the Somnia Mini Hackathon to demonstrate how blockchain data can be more than just numbers—it can be art.
§ The Concept
The core of the application is reactivity. The site functions as a digital conductor, using a Pentatonic Scale to ensure every "beat" from the blockchain sounds harmonious and intentional.
-Real-Time Pulse: The app uses a WebSocket (WSS) to listen for every new block on the Somnia Testnet.
Audio Synthesis: Each block triggers a specific note from the scale, creating a continuous, unrepeatable melody.
Visual Ripples: Block pulses trigger blue ripples, while user transactions trigger high-intensity pink ripples (255, 105, 180).
Ambient Idle Mode: Even when the network is quiet, a steady "A1" bass pulse and random synth notes ensure the "party" never stays silent.
§ Technical Stack
Blockchain: Somnia Testnet.
Frontend: Next.js, Tailwind CSS, and Lucide React.
Web3 Interaction: Ethers.js (v5) for wallet connection and transaction handling.
Audio Engine: Tone.js for browser-based polyphonic synthesis.
Visuals: HTML5 Canvas for real-time ripple rendering.
🎨 Aesthetic Direction
The project follows a Cyber Symphony and Dark Academia palette:
Primary Colors: Deep Purple (#B19CD9), Neon Blue (#6FD5FF), and Hot Pink (#FF69B4).
Vibe: Lo-fi, luxury, and neon-lit digital space.
§ How to Run
Initialize: Open the site in a Web3-enabled browser (like OKX Wallet or MetaMask).
Sync: Click "INITIALIZE SYSTEM" to connect your wallet and start the audio context.
Conduct: Watch the live block feed and click "SEND 0.0005 STT" to add your own pulse to the symphony.
Built by Senseii_ciel
