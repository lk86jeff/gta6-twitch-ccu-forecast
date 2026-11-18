# GTA VI Twitch CCU Forecaster

Autonomous high-precision forecaster for live concurrent Twitch viewer counts during release day.
Built for the make.fun `gta6-twitch-ccu-forecast-01` competition.

## Architecture
- Fast Node.js standalone engine (<20ms runtime)
- Multi-tier rolling unlock diurnal factor composite model
- Log-scale calibrated quantile distribution
