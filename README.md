# Travel Maestro

Travel Maestro is an advanced trip planning tool that leverages multi-agent AI technology to provide comprehensive travel itineraries based on user preferences. Utilizing the CrewAI framework, this tool orchestrates multiple specialized agents to gather information, analyze options, and deliver a personalized and detailed travel plan. Whether you're deciding between cities or looking for the best local experiences, Travel Maestro ensures your trip is planned with precision and tailored to your interests.

## Features

- **Python Packaging & Dependency Management**: Utilized Poetry for efficient packaging and dependency management, ensuring streamlined development and deployment processes.
- **API Integration**: Implemented SERP API for advanced search capabilities and developed custom calculator tools for accurate mathematical computations within the agent framework.
- **Multi-Agent Architecture**: Designed and created a multi-agent system using the CrewAI framework, facilitating communication and task assignment among specialized agents.
- **Expert Agents**: Developed specialized agents such as `expert_travel_agent`, `city_selection_expert`, and `local_tour_guide` to provide comprehensive travel planning and logistics services.
- **User Interaction & Customization**: Gathered user preferences through interactive inputs and designed an intelligent system to generate tailored travel itineraries, enhancing user experience and satisfaction.

## Tools and Agents

- **Tools**: BrowserTools, CalculatorTools, SearchTools
- **Agents**: `city_selection_agent`, `travel_concierge`, `local_expert`

## Usage

1. **Install dependencies** using Poetry:
   ```bash
   poetry install
   ```

2. **Run the application**:
   ```bash
   python main.py
   ```

3. **Interact with the system** through the CLI or web interface (if applicable).

4. **Input your travel preferences**, including origin, potential destination cities, interests, and travel dates.

5. **Receive detailed reports and itineraries** generated by specialized agents, tailored to your preferences.


## Contributing

We welcome contributions from the community. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
