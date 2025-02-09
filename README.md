# Holy Cow! Crew - Remastered

## Overview
This project implements a multi-agent system using CrewAI to optimize operations for the Holy Cow! restaurant chain in Switzerland. The system leverages existing sales prediction data to provide comprehensive resource optimization and business intelligence.

## Key Features
- Performance Analysis
- Resource Optimization
- Advanced Reporting System
- Market Strategy Analysis

## Project Structure
```
└── holy-cow-crew/
    ├── src/
    │   ├── agents/            # Individual agent implementations
    │   ├── tools/             # Custom tools for agents
    │   ├── models/            # Pydantic models
    │   └── flows/             # CrewAI flow definitions
    ├── tests/                 # Test suite
    └── docs/                  # Documentation
```

## Setup & Installation
```bash
# Clone the repository
git clone https://github.com/Yasmani-Cascante/holy-cow-crew-remastered.git
cd holy-cow-crew-remastered

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
from holy_cow_crew.flows import RestaurantOptimizationFlow

flow = RestaurantOptimizationFlow()
results = flow.kickoff()
```

## Testing
```bash
python -m pytest tests/
```

## Contributing
Contributions are welcome! Please read our Contributing Guidelines for details.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Yasmani Cascante - [GitHub Profile](https://github.com/Yasmani-Cascante)