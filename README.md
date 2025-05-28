# Quality Intelligence System (QIS) 
** QIS is a desktop application built with WPF and Prism (MVVM pattern) to help quality control teams manage, analyze, and visualize measurement data in a manufacturing environment.

This system enables engineers and QA personnel to track quality performance, identify trends, and make data-driven decisions with confidence.

## 🧩 Key Features
- 🧪 **Measurement Data Management**

  - Import measurement data from files (JSON, CSV)

  - Support for real-time or manual data entry

  - Validation rules for numeric, range-bound, and mandatory fields


- 📊 **Dynamic UI Based on Input Type**

  - Adaptive field visibility based on selected type (e.g., Type A / Type B)

  - 53+ input fields using `ReactiveProperty<double?>` for full control and validation


- 📋 **Immediate Validation Feedback**

  - Instant error messages for incorrect or missing values

  - Custom validation rules: required, numeric formats (F3/F0), positive numbers, range checks


- 💾 **Load/Save Functionality**

  - Auto-fill form by loading data from a JSON file (e.g., A.json)

  - Save validated results to structured JSON for recordkeeping


- 📈 **Integration with Reference Limits**

  - Compare input values with limits from `B.json`

  - Highlight out-of-spec values


## 🛠️ Technology Stack
- **.NET Framework / .NET Core**

- **WPF (Windows Presentation Foundation)**

- **Prism (MVVM Architecture)**

- **ReactiveProperty**

- **Newtonsoft.Json** (JSON parsing)

- **XAML** for UI definitions
