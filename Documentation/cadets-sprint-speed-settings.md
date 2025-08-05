# Cadets Sprint Speed Settings

For **cadets** (no ladder, just sprint to the tower), you’ll want your in‑game speeds to feel fast and athletic but still grounded in real human sprinting.

- [How to Implement Running](https://www.youtube.com/watch?v=EG9iYYraDgw)

Here’s how it maps in real life:

## 1. **Real Fire Sport Cadet Sprint**

* **Distance**: Usually \~30–35 meters to the tower base.
* **Top speed**: A 12–14‑year‑old in good shape can hit **6–8 m/s** (21–29 km/h) over short bursts.
* **Time to reach ladder**: \~4–5 seconds in real competitions.

---

## 2. **UE5 Speed Conversion**

In UE, default `CharacterMovement` speeds are in **cm/s**:

* **500** = 5 m/s → \~18 km/h (fast jog pace).
* **1200** = 12 m/s → \~43 km/h (unrealistic for humans).

---

## 3. **Recommended for Cadets**

| Action  | Speed (cm/s) | m/s     | Notes                              |
| ------- | ------------ | ------- | ---------------------------------- |
| Walk    | 300–350      | 3–3.5   | Casual walk, warm‑up movement      |
| Jog/Run | 550–600      | 5.5–6   | Moderate run                       |
| Sprint  | 750–850      | 7.5–8.5 | Max burst speed for young athletes |

This keeps the sprint **realistic but still exciting** — enough to feel quick in‑game without “video game cheetah mode.”

---

## 4. **Game Feel Tweaks**

* Add **acceleration curve** so sprint builds over \~0.5 sec, not instantly.
* Keep **sprint stamina** short for cadets — \~4–5 seconds before they slow to \~600 cm/s.
* Use **head bob + breathing** SFX to sell the effort.

---

If you want, I can do the **next stage** for **teen/adult beginners** carrying a ladder — where sprint speed is slower but momentum matters — so you can set both now and keep a consistent scale across all player types.