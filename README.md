# Accademium Orientation Survey Prototype

- 👉🏻 [Live Preview](https://accademium-orientation-survey-final.vercel.app/)
- 🎥 [Video Walkthrough - Kaltura](https://video.hanze.nl/mediashare/f4f20c2fc590902b/media/Video_Walkthrough_Ivan_Patarov_414334/0_v85jexzk)
- 📺 [Video Walkthrough - YouTube](https://www.youtube.com/watch?v=YJXvXG9lRYE)

## Overview

This document outlines the final version of the prototype for "Accademium", specifically focusing on the Orientation Survey component. This prototype represents a significant evolution from the initial high-fidelity click-through designs created in Adobe XD and Figma, where survey results were predetermined. The current version captures, stores, and utilizes user responses in real-time to generate personalized recommendations for study fields, programs, countries, cities, and universities.

## Purpose

The primary aim of this prototype is to demonstrate the complex type of interactivity within the Accademium platform. It showcases how user responses are handled, stored, and used to provide tailored recommendations based on individual preferences, strengths, and interests.

## Functionality

#### 1. User Interaction and Local State Management:

- Users interact with an orientation survey designed to capture their preferences, strengths, and interests.
- As users progress through the survey, their responses are stored in the local state of the application in real-time, ensuring accuracy and responsiveness. 

#### 2. Integration with OpenAI API:

- Upon completing the survey, the local state (containing the user's responses) is sent to the OpenAI API.
- The AI model processes the responses and generates personalized recommendations for study fields, programs, countries, cities, and universities.

#### 3. Enhanced User Experience:

- A back button has been added to allow users to revisit previous questions, improving flexibility and reducing unnecessary API calls.
- Users are provided with immediate updates and feedback based on their inputs, enhancing the overall user experience.

#### 4. Dashboard Navigation:

- A new dashboard feature allows users to switch to an overview of their personalized recommendations at any point during the survey.
- Users can review and navigate their journey flexibly, without being restricted to a linear process.

## Features

#### 1. High-Fidelity User Interface

- Enhances the visual and interactive elements from the hi-fi prototype, ensuring a polished and engaging user experience.
- Utilizes intuitive design principles to guide users seamlessly through the orientation survey and recommendation process.

#### 2. Real-Time Data Handling

- Captures and manages user responses in real-time, maintaining data accuracy and security throughout the survey interaction.
- Allows users to review and adjust their answers before final submission, fostering thoughtful responses.

#### 3. AI-Driven Recommendations

- Employs OpenAI's advanced models to analyze user data and generate personalized study field recommendations.
- Provides tailored suggestions based on user preferences and survey responses, aiding users in making informed academic decisions.

#### 4. Gamification with User Control

- Introduces a prominent progress bar as a form of extrinsic motivation, encouraging users to continue through the process.
- Incorporates a retry button with a confirmation prompt, preventing accidental restarts of the survey.
- The "Randomize" feature has been replaced with the dashboard button for more accurate and user-aligned recommendations.

#### 5. Upcoming Features

- An AI chatbot button is under development to provide real-time assistance during the survey.

## Installation

You can access the prototype directly from [this link](https://accademium-orientation-survey-final.vercel.app/).

Alternatively, you can run the prototype locally:

**IMPORTANT:** Ensure Node.js is installed. Download it here: https://nodejs.org/en

1. Navigate to the `accademium-orientation-survey-final` folder.
2. Open a terminal (e.g., Git Bash) and ensure you are inside the `accademium-orientation-survey-final` folder.
3. Run `npm install` to install the necessary dependencies.
4. After the installation is complete, run the command `npm run dev` in the terminal.
5. Open your preferred web browser and go to `localhost:5173` to access the prototype.

## Usage

The application utilizes the OpenAI API, and each API call costs approximately **~$0.01**. A typical session generally totals around **~$0.02** due to making two separate calls - one for the initial study field recommendations and another for the dashboard navigation.

The application currently operates within a budget of approximately **$5 dollars**, so please use it sparingly.

Additionally, if you are running the application from a location other than the live preview link or the folder provided in the graduation hand-in, you will need to generate your own API key for the OpenAI API.

For further instructions on generating an API key and additional information on usage guidelines, please consult the [OpenAI documentation](https://platform.openai.com/docs/overview).

## Future Development

- Implement additional gamification elements to further enhance user engagement and interaction.
- Enhance AI capabilities to provide even more personalized and accurate recommendations.
- Gather user feedback to continually refine and improve the prototype's usability and functionality.
