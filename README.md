# Dayfall: a weather forecast for your energy

Built by **Animesh Ojha** for the Mosaic Wellness CEO's Office Builder Round.

Dayfall turns four sliders (sleep, energy, stress, mood) into an energy score, a forecast for the day, and one 60-second ritual to act on.

## Run it
Open `index.html` in any browser. There is no build step, backend or install.

## How it works
- Score (0-100) = sleep (30) + energy (30) + low stress (25) + mood (15).
- Forecast: morning, midday, 3 pm dip and evening, adjusted by sleep debt and stress.
- Ritual: box breathing for high stress, light and water for short sleep, a movement snack for low energy, or a plan to protect a good day.
- History is stored in the browser's localStorage only. No data leaves the device.

## Limitation
The scoring is a simple rule-based model, not clinically validated. This is wellness guidance, not medical advice.
