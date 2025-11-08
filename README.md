import "../styles/globals.css";

export default function MyApp({ Component, pageProps }) {
  // enable sandbox flag for Pi dev testing
  if (typeof window !== "undefined") window.__PI_SANDBOX = true;
  return <Component {...pageProps} />;
}
# POWANET v3 — Quantum Global Edition (demo)

This repository is a sandbox-ready demo for POWANET v3 (mobile-first).
Features:
- Mixed Testnet/Mainnet demo mode
- EGO voice/text assistant stub
- 25 networks grid
- Dual wallet demo (Pi + POWA token)
- Safe default settings for Pi App Studio

Deploy:
- Add OPENAI_API_KEY in host/env for real AI replies (optional).
- Use Vercel or CodeSandbox preview URL as Pi App Studio development URL.
