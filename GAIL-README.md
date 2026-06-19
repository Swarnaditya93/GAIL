# GAIL Pipeline Maintenance — Weather Risk Predictor

A prototype built during my internship at **GAIL (India) Limited**, as part of a 3-intern team, to reduce the risk of scheduling pipeline repair work on days when weather conditions turn unsafe.

## Problem

GAIL's pipeline network stretches across the country and passes through widely varying climatic zones. Repair and maintenance work is typically planned a day in advance — but weather can shift overnight. If a repair is scheduled and the next day's conditions (heavy precipitation, extreme temperature, high humidity, etc.) make the site unsafe to work in, teams either proceed under unsafe conditions or face last-minute, costly rescheduling. Either outcome carries real risk to worker safety and operational continuity.

## What this does

Given a location along with the current day's temperature, humidity, and precipitation, the app predicts whether working conditions at that site are likely to be safe and suitable for repair work the **next day** — flagging the risk early enough for teams to reschedule proactively instead of finding out on-site.

## My contribution

This was a team project built with two other interns. My focus was **data collection and preprocessing** — sourcing and cleaning the weather data (temperature, humidity, precipitation) used to drive the predictions.

## Tech stack

- Python
- Streamlit (web app interface)
- Pandas

## Status

This is a working **prototype / proof of concept** built for an internship evaluation, not a production deployment. It demonstrates the approach for early-warning weather risk flagging on planned maintenance work.

## Running locally

```bash
pip install -r requirements.txt
streamlit run app.py
```
