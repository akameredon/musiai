# MusiAI

**Identity-locked AI music & video platform**  
Live: https://musiai.netlify.app/

## Vision
- Artists create AI music and AI video
- Live natural-voice capture at signup → voice fingerprint
- Every upload must match that voice or it cannot earn
- Videos use the artist’s own likeness
- Listeners pay **$0.50/month**
- Artists earn from streams of verified tracks
- No bots. Real humans only. AI is the instrument, not the identity

## What this MVP does
1. Artist / listener signup (local accounts)
2. Live mic voice capture (Web Audio / MediaRecorder)
3. Upload AI audio or video file
4. Voice-match gate — pass → earning enabled; fail → blocked
5. Discover feed of verified tracks only
6. Stream button increments streams + demo earnings
7. Listener subscribe flow ($0.50/mo demo)

## Run locally
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Deploy
Connected to Netlify: https://musiai.netlify.app/
