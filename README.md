### Contribution Overview
My primary responsibility within the NeuroLog project focused on developing the core study environment and implementing AI-assisted learning components. The main objective was to seamlessly connect the user's learning experience with our adaptive system, while exploring and integrating local AI to support educational activities.

### Key Responsibilities

#### 1. Study Environment Architecture
Developed the dedicated study environment utilized by learners when engaging with individual topics. This modular workspace provides a structured interface for:
* Topic-based learning navigation
* Study content access and management
* Note-taking capabilities
* Interactive learning sessions
* Revision preparation
* Foundation for future assessment functionalities

#### 2. Application Integration
Integrated the localized study environment into the broader NeuroLog application architecture. This required synchronizing various data points and user interfaces, including:
* Selected topics and subject metadata
* Core study materials and user notes
* Active learning session tracking
* Extensible hooks for future assessment features

#### 3. AI Implementation
Engineered the integration of local AI capabilities to power the platform's assisted learning features. 
* **Runtime Environment:** Ollama
* **Selected Model:** Qwen2.5:7B

### Local AI Setup Instructions
To utilize the AI-assisted learning functionality locally, ensure Ollama is installed on your system. Once installed, execute the following command to download the required model: Qwn2.5:7b.

```bash
ollama pull qwen2.5:7b
