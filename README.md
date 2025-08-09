# INTERFACCE — Chromatic Field

A browser-native chromatic landscape reacting to **voice**, **movement**, and **presence** — inspired by light/color installations.

**Try locally**
- VS Code + *Live Server* → Open with Live Server
- Or python http server:
  ```bash
  python3 -m http.server 5173
  # then open http://localhost:5173/
  ```

**Deploy to Vercel (static)**
1. Create a repo and push these files.
2. Connect the repo on Vercel → Framework: **Other**, Build: **None**, Output: **/**.
3. Ensure `vercel.json` is included (adds a Permissions-Policy header).

**Deploy to GitHub Pages**
1. Repo → Settings → Pages:
   - Source: *Deploy from a branch*
   - Branch: `main` (root)
2. Visit: `https://<your-user>.github.io/<repo>/`

**Interactions**
- Mouse → refraction lens
- Microphone → energizes saturation & flow
- Webcam → ambient hue shifts color temperature
- **C** palette | **M** mute | **S** save snapshot | **H** toggle HUD
- Language switcher ITA/ENG in the bottom-right corner

**Notes**
- Microphone/Camera require HTTPS or `localhost` and a user gesture (button click).
- Some browser previews (iframes) block permissions; open the page directly.

**Credits**
Design & code: Christian Pezzin · Project: *INTERFACCE — Chromatic Field*
