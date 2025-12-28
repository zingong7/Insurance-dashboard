# 📊 PRISM Insurance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge)

A comprehensive Power BI dashboard for analyzing insurance data with interactive visualizations, drill-through capabilities, and row-level security implementation.

---

## 📑 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dashboard Components](#dashboard-components)
- [Key Metrics](#key-metrics)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Security Features](#security-features)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

This Power BI dashboard provides comprehensive insights into PRISM Insurance Pvt. Ltd.'s operations, enabling data-driven decision-making across premium collection, coverage distribution, claims processing, and policy management.

**Built With:**
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Row-Level Security (RLS)
- Interactive Drill-Through Pages

---

## ✨ Features

- ✅ **Interactive Filters** - Filter by CustomerID, ClaimNumber, and PolicyNumber
- ✅ **Drill-Through Functionality** - Deep dive into policy type details
- ✅ **Row-Level Security (RLS)** - Policy type-based data access control
- ✅ **Multi-Page Layout** - Organized information architecture
- ✅ **Real-time KPIs** - Monitor key performance indicators
- ✅ **Visual Analytics** - Charts, graphs, and tables for comprehensive analysis
- ✅ **Dynamic Filtering** - Cross-visual filtering enabled
- ✅ **Mobile Responsive** - Optimized for mobile viewing

---

## 📊 Dashboard Components

### 1. Gender Distribution
Visual cards showing policy distribution by gender (Female/Male)

### 2. Claims by Status
Area chart tracking claim volumes across:
- Rejected
- Settled  
- Pending

### 3. Premium Amount by Policy Type 🔍
Horizontal bar chart displaying premium distribution:
- **Travel**: 2.5M
- **Health**: 1.2M
- **Auto**: 1.0M
- **Life**: 0.7M
- **Home**: 0.6M

> **⚡ Drill-Through Enabled**: Right-click any bar for detailed analysis

### 4. Active/Inactive Policies
Donut chart showing policy status distribution with percentages

### 5. Claim Amount by Age Group
Line chart analyzing claim trends across demographics:
- Young Adults
- Adult
- Senior

### 6. Policy Performance Matrix
Detailed table displaying Pending, Rejected, Settled amounts and settlement ratios by policy type

---

## 📈 Key Metrics

| Metric | Value | Description |
|--------|-------|-------------|
| 💰 Total Premium | 5.98M | Total premium amount collected |
| 🛡️ Total Coverage | 600.55M | Total coverage amount provided |
| 📋 Total Claims | 16.91M | Total claims processed |
| ✅ Active Policies | 4.61K (46.06%) | Currently active policies |
| ❌ Inactive Policies | 5.4K (53.94%) | Inactive/expired policies |

---

## 🚀 Getting Started

### Prerequisites

- Power BI Desktop (Latest version)
- Microsoft Account with Power BI Service access
- Data source credentials
- Appropriate permissions for insurance data access

### System Requirements

- **OS**: Windows 10 or later
- **RAM**: Minimum 4GB (8GB recommended)
- **Storage**: 500MB free space
- **Internet**: Required for publishing and sharing

---

## 💻 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/zingong7/prism-insurance-dashboard.git
cd prism-insurance-dashboard
```

### Step 2: Open in Power BI Desktop

1. Launch Power BI Desktop
2. Open the `.pbix` file from the cloned repository
3. Enter data source credentials when prompted
4. Click **Refresh** to load the data

### Step 3: Publish to Power BI Service (Optional)

1. Click **File** → **Publish** → **Publish to Power BI**
2. Select your workspace
3. Wait for publishing to complete
4. Configure scheduled refresh if needed

---

## 🔒 Security Features

### Row-Level Security (RLS)

This dashboard implements RLS based on **PolicyType** to ensure users only access authorized data.

#### Implemented Roles:

- **Auto Insurance Team** - Access to Auto policy data only
- **Health Insurance Team** - Access to Health policy data only
- **Life Insurance Team** - Access to Life policy data only
- **Home Insurance Team** - Access to Home policy data only
- **Travel Insurance Team** - Access to Travel policy data only
- **Management** - Full access to all policy types

#### How RLS Works:

1. **Data Filtering**: Users see only data matching their assigned policy type
2. **Automatic Enforcement**: Security rules apply automatically when users access the dashboard
3. **Role Assignment**: Administrators assign users to roles in Power BI Service
4. **Testing**: Use "View as Role" feature in Power BI Desktop to test security

#### Setting Up RLS:

**In Power BI Desktop:**
1. Go to **Modeling** → **Manage Roles**
2. View existing roles and their filter expressions
3. Test roles using **Modeling** → **View as**

**In Power BI Service:**
1. Navigate to the dataset
2. Click **Security** (•••)
3. Add users/groups to appropriate roles
4. Save changes

---

## 🔍 Drill-Through Feature

### Premium Amount by Policy Type Chart

The horizontal bar chart supports drill-through functionality for detailed analysis.

**How to Use:**
1. Right-click on any policy type bar (Travel, Health, Auto, Life, or Home)
2. Select **Drill through** from the context menu
3. Navigate to the detailed analysis page
4. View granular data for the selected policy type
5. Use the back button to return to the main dashboard

**What You'll See:**
- Detailed policy breakdowns
- Customer-level information
- Premium trends over time
- Claim details for the selected policy type

---

## 📱 Usage

### For Business Analysts
- Use interactive filters to analyze specific customer segments
- Right-click on visualizations to drill through for deeper insights
- Monitor KPIs and identify trends
- Export data for further analysis

### For Managers
- Review high-level metrics on the main dashboard
- Track policy performance across different types
- Analyze active vs. inactive policy trends
- Monitor claim settlement ratios

### For Administrators
- Manage RLS roles and user assignments
- Schedule data refreshes
- Monitor dashboard performance
- Ensure data security compliance

---

## 📸 Screenshots

> Add your dashboard screenshots here

```
![Main Dashboard](images/dashboard-main.png)
![Drill-Through Page](images/drill-through.png)
![Filters](images/filters-demo.png)
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 Authors

- **Adnan Mohiddin** - *Initial work* - [zingong7](https://github.com/zingong7)

---

## 📧 Contact

For questions or support:

- **Email**: arsadnan75@gmail.com
- **GitHub Issues**: [Create an issue](https://github.com/zingong7/prism-insurance-dashboard/issues)
- **GitHub Profile**: [@zingong7](https://github.com/zingong7)

---

## 🙏 Acknowledgments

- Power BI Community for inspiration and best practices
- Microsoft Documentation for technical guidance
- PRISM Insurance Pvt. Ltd. for the use case

---

## 📊 Project Status

**Current Version**: 1.0  
**Last Updated**: December 2025  
**Status**: Active Development

### Roadmap
- [ ] Add predictive analytics for claim forecasting
- [ ] Implement real-time data refresh
- [ ] Create mobile-optimized layouts
- [ ] Add customer segmentation analysis
- [ ] Integrate external market data sources

---

⭐ **If you find this project useful, please consider giving it a star!** ⭐
