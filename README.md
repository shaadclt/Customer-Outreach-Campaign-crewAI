# CrewAI Sales Outreach and Lead Profiling

This repository demonstrates the use of CrewAI to enhance sales outreach and lead profiling using a combination of advanced AI agents and tools. The project leverages CrewAI agents and LangChain to identify high-value leads and craft personalized outreach campaigns.

## Project Overview

The project consists of two primary tasks:
1. **Lead Profiling**: Analyzing potential leads to compile detailed profiles based on available data.
2. **Personalized Outreach**: Creating customized communication strategies to engage key decision-makers effectively.

## Installation

To run this project, you'll need to install the required Python packages. This involves using the `pip` package manager to install specific versions of the CrewAI, CrewAI tools, and LangChain libraries.

## Setup

1. **Google Colab Environment Variables**: The project requires API keys for Groq and Serper services. These keys should be set as environment variables in the Google Colab environment. This allows secure access to external services without hardcoding sensitive information.

2. **Import Libraries and Initialize Agents**: Import necessary libraries and define the agents. There are two main agents:
   - **Sales Representative Agent**: This agent is responsible for identifying high-value leads that match the ideal customer profile. It uses advanced data analysis and trend identification to uncover potential opportunities.
   - **Lead Sales Representative Agent**: This agent focuses on nurturing leads by crafting personalized and compelling communications. It aims to convert interest into actionable commitments by creating engaging messages tailored to the specific needs and culture of potential clients.

3. **Define Tools**: Various tools are used to support the agents' tasks, such as reading directories, reading files, and performing web searches. Additionally, a sentiment analysis tool is defined to ensure the communication is positive and engaging.

4. **Define Tasks**:
   - **Lead Profiling Task**: This task involves conducting an in-depth analysis of a lead company, including their background, key personnel, recent milestones, and potential needs. The goal is to compile a comprehensive profile that will inform the engagement strategy.
   - **Personalized Outreach Task**: Using the insights from the lead profiling task, this task involves crafting a personalized outreach campaign. The campaign is tailored to the key decision-maker in the lead company, addressing their recent milestones and demonstrating how our solutions can support their goals.

5. **Create and Run Crew**: The Crew object is created by combining the defined agents and tasks. The `kickoff` method is used to execute the tasks with specific inputs. The output includes a comprehensive lead profile and personalized email drafts targeting the key decision-maker.

## Example Output

After running the tasks, the output will include:
- A comprehensive lead profile that provides detailed information about the potential lead, including company background, key personnel, recent business developments, and identified needs.
- Personalized email drafts designed to engage the key decision-maker, addressing their specific milestones and how our solutions can support their goals.

## Usage

To use this notebook:
1. **Clone the Repository**: Download the repository to your local machine or directly open it in Google Colab.
2. **Set Environment Variables**: Ensure the required API keys for Groq and Serper services are set in your Google Colab environment.
3. **Run the Cells**: Execute the cells in the notebook sequentially to perform lead profiling and generate personalized outreach content.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

## Acknowledgments

- **CrewAI**: For providing the platform to build and execute advanced AI agents.
- **LangChain**: For facilitating integration with Groq models.
- **TextBlob**: For sentiment analysis functionalities.

## Contact

For questions or feedback, please open an issue or contact [shaadclt@gmail.com](mailto:shaadclt@gmail.com).
