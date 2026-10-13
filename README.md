# AI Smart Wardrobe

## Project Overview
A web-based AI virtual closet that digitizes a user's real wardrobe, recommends personalized outfits based on weather, occasion, preferences, and wardrobe history, and lets the user preview selected garments on themselves through virtual try-on.

## Project Goals：AI Virtual Closet & Styling Assistant
1. Core Vision
Develop a mobile-first web application that digitizes users' wardrobes, provides personalized AI-driven outfit recommendations based on real-time context, and visualizes pairings via 2D virtual try-on technology.

2. Key Functional Goals
- Wardrobe Digitization: Enable easy photo uploads with automatic background removal. Use Vision-Language Models for automatic clothing tagging (category, color, style), with manual edit capabilities for accuracy.
- AI Outfit Recommendation (Core Feature A): Build a hybrid (Rule-based + LLM) recommendation pipeline. Generate 2-3 outfit options based on real-time weather, specific occasions, style preferences, or a chosen "anchor piece," complete with AI explanations.
- 2D Virtual Try-On (Core Feature C): Integrate stable 2D diffusion models (2D VTON) to visualize selected garments on a user's base photo, intentionally avoiding high-risk 3D physics simulations to ensure demo stability.
- Outfit Calendar & Analytics: Track daily OOTDs (Outfit of the Day) in a calendar view and automatically calculate wear frequencies to provide insights into wardrobe utilization.

3. Technical & Product Scope

- Product Format: Responsive Web App designed for mobile UI but optimized for desktop presentations (no native app packaging required).
- System Architecture: Integrate a modern frontend (e.g., React/Next.js) with a cloud database, real-time weather APIs, and third-party/open-source AI models (segmentation, classification, LLM, 2D VTON).
- Target Use Case: A single-user live demo showcasing the complete user journey: Upload -> Auto-tag -> Select Occasion/Weather -> AI Recommend -> 2D Try-On.

4. Deliverables & Course Objectives
- Deliver a stable, **working prototype** within the given timeframe (2-person team).
- Provide a well-structured GitHub repository with a clear commit history.
- Deliver a final presentation clearly articulating the **technical contributions** and **practical impact**, emphasizing the integration of AI logic with the try-on visualization.

## Project Status
Initial setup and planning.

## Course
Applied Deep Learning and AI - Fall 2026
