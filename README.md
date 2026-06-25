# 2026-Hunt-Alerts
2026 Hunting SMS - N8N
# Bear Hunt SMS Alerts

An automated n8n workflow that delivers concise SMS weather forecasts and bear harvest quota updates.

This project combines National Weather Service forecast data, AI-powered weather summarization, and publicly available bear harvest information into short SMS messages suitable for use in the field.

---

## Features

- Daily weather summaries using National Weather Service data
- AI-generated weather summaries using Claude Haiku
- Automated bear harvest quota monitoring
- SMS delivery
- Fully automated scheduled workflow
- Easy to customize for other hunt areas

---

## Technologies

- n8n
- Anthropic Claude Haiku
- National Weather Service API
- Utah Division of Wildlife Resources harvest data
- Textbelt SMS

---

## Workflow

1. Retrieve forecast location
2. Download the next 24 hours of weather
3. Summarize the forecast using Claude Haiku
4. Send weather SMS
5. Retrieve current bear harvest information
6. Build harvest summary SMS
7. Send harvest update SMS

---

## Configuration

Before running the workflow, configure:

- SMS provider credentials
- Anthropic API credentials
- GPS coordinates
- Hunt unit
- Schedule trigger

---

## Example Weather SMS

24hr Fcst - 9/18 6am: Low 38°F. Gusts 20 mph afternoon. Slight chance of afternoon thunderstorms. High 67°F.

---

## Example Harvest SMS

Date: 9/18/2026

Time: 5:00 AM MT

Unit: Bear Hunt

Status: Open

Quota: 20

Harvest to date: 7

Remaining: 13

---

## Repository Structure

```
workflows/
docs/
screenshots/
README.md
LICENSE
.env.example
```

---

## License

Released under the MIT License.