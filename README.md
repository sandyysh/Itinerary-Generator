## OpenAI Itinerary Generator

### Project Description

The AI Itinerary Generator is an application that utilizes the OpenAI API model "text-davinci-003" to generate personalized travel itineraries. The user provides input regarding their destination, food preferences, and activity preferences, and the application generates a detailed itinerary for each day of their trip. The generated itinerary includes recommendations for activities, along with descriptions and shortened Google Maps links, as well as recommendations for lunch and dinner restaurants.

### Why We Chose the Technologies

- OpenAI API:
    - Flexibility and adaptability: The OpenAI model can be refined based on user prompts and can respond accordingly. It has access to a wide range of information and can provide details about various destinations, attractions, and logistical information.
    - Convenience: Instead of searching multiple sources and manually compiling information, the OpenAI model can provide personalized recommendations based on user preferences.
- Google Maps Places API: I used this API to fetch a list of countries and cities in the world for users to select from. This helps ensure accurate and comprehensive destination options.
- React: React is a popular JavaScript library for building user interfaces, and it provides a convenient and efficient way to develop dynamic web applications.
- Ant Design: I used Ant Design, a React UI library, to enhance the visual appearance and user experience of the application. Ant Design offers a wide range of pre-designed components and a consistent design system, which helps in building a professional and user-friendly interface.

### Challenges Faced and Future Improvements

- Outdated information: One of the challenges I encountered is that the information provided by the OpenAI model is only updated until 2021. This means that the generated links and information may be outdated. To address this, I plan to integrate other APIs that provide more up-to-date information or booking capabilities.
- Lack of visual content: As a language model, OpenAI does not provide images or reference maps, which are often critical when planning a trip. In the future, I aim to integrate with other tools or APIs that can provide visual content and enhance the overall user experience.
- Speed optimization

### How to Install and Run the Project

To install and run the project, follow these steps:

1. Set up the required dependencies and environment:
    - Clone the project repository to your local machine.
    - Install the necessary packages and dependencies eg. antd, react-dom, using the package manager of your choice (e.g., npm or yarn).
    - Set up a local environment file and enter your Google Maps API and OpenAI API keys.
2. Obtain API keys:
    - Visit the official documentation for Google Maps API and OpenAI API to learn how to obtain your respective API keys.
3. Configure the environment:
    - In your local environment file, enter your API keys.
4. Run the project:
    - Start the development server using the appropriate command for your package manager.
    - Access the application through your web browser at the provided local address.

Please note that this is a high-level guide, and additional steps or configurations may be required based on your specific development environment and project setup. Refer to the project's documentation for more detailed instructions.
