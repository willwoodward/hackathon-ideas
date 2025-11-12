# Disaster Detection from Social Media

## Problem Statement
During earthquakes, hurricanes, or floods, official channels often take time to assess damage and coordinate responses. Social media posts can provide immediate insights about affected areas and urgent needs, but the volume of data makes manual monitoring impossible. This project challenges participants to build tools that detect, classify, and visualize disaster-related information from social media in real-time.

## Background
During recent earthquakes in Jamaica and other regions, delayed situational awareness contributed to slower aid delivery and higher casualties. Real-time analysis of posts (text, images, geotags) can inform emergency services and humanitarian organizations.

## Datasets
- Twitter API (real-time or historical tweets filtered by disaster keywords)  
- Geo-tagged disaster tweets datasets (e.g., CrisisLexT26: https://crisislex.org/data-collections.html)  
- OpenStreetMap for location context

## Suggested Approaches
- Natural Language Processing (NLP) to classify tweets as “urgent need”, “damage report”, or “general discussion”.  
- Geospatial clustering to map affected areas.  
- Sentiment analysis or image classification to identify severity.  
- Dashboard for emergency responders to visualize hotspots and trending needs.

## Difficulty
Medium to Hard

## Potential Impact
Real-time disaster detection could improve resource allocation, speed up emergency response, and save lives by providing authorities and NGOs with actionable information faster than traditional reporting channels.

## Submission / Deliverables
- Interactive map or dashboard of disaster-affected areas.  
- NLP and/or image classification pipelines.  
- Documentation explaining data sources, methodology, and potential integration with emergency response workflows.
