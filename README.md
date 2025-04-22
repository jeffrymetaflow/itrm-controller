# ITRM Controller Module

This is the centralized controller class used to coordinate shared logic between ITRM platform modules, including:

- Component management
- Architecture linking
- Risk simulation
- Forecast generation
- AI assistant context formatting

## 🔧 Usage Example

```python
from controller import ITRMController

controller = ITRMController()

controller.add_component({
    "Name": "Firewall A",
    "Category": "Cybersecurity",
    "Spend": 20000,
    "Revenue Impact %": 15,
    "Risk Score": 70
})

controller.run_simulation()
print(controller.simulation_results)
