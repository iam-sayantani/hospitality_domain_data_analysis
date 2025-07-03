# Hospitality Data Analysis

## Overview

This project is created for the free training for non tech to Machine Learning trainning session. This project provides comprehensive data analysis tools and insights for the hospitality industry, focusing on hotel performance metrics, guest satisfaction, revenue optimization, and operational efficiency. The analysis covers key performance indicators (KPIs) essential for hospitality management decision-making.

## Key Features

- **Revenue Analytics**: ADR (Average Daily Rate), RevPAR (Revenue per Available Room), and occupancy rate analysis
- **Guest Satisfaction Analysis**: Review sentiment analysis, rating trends, and feedback categorization
- **Operational Metrics**: Booking patterns, cancellation analysis, and seasonal demand forecasting
- **Competitive Analysis**: Market positioning and pricing strategy insights
- **Customer Segmentation**: Guest demographic analysis and behavior patterns

## Dataset Description

The analysis utilizes hospitality datasets containing:

- **Booking Data**: Reservation details, check-in/check-out dates, room types, pricing
- **Guest Information**: Demographics, booking channels, loyalty status
- **Revenue Data**: Daily rates, total revenue, ancillary services income
- **Review Data**: Guest ratings, comments, review platforms
- **Operational Data**: Occupancy rates, staff metrics, facility utilization

## Technical Stack

- **Python 3.8+**: Primary programming language
- **Pandas & NumPy**: Data manipulation and numerical analysis
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning and predictive analytics
- **Plotly**: Interactive visualizations
- **NLTK/spaCy**: Natural language processing for review analysis
- **Jupyter Notebook**: Interactive analysis environmen

### 1. Revenue Optimization
- **ADR Analysis**: Track average daily rates across different periods and room types
- **RevPAR Calculation**: Monitor revenue per available room for performance assessment
- **Pricing Strategy**: Analyze optimal pricing based on demand patterns and competitor rates

### 2. Guest Experience Analytics
- **Satisfaction Metrics**: Calculate NPS (Net Promoter Score) and satisfaction ratings
- **Review Sentiment**: Analyze guest feedback using natural language processing
- **Service Quality**: Identify areas for improvement based on guest comments

### 3. Operational Efficiency
- **Occupancy Patterns**: Analyze booking trends and seasonal variations
- **Channel Performance**: Evaluate effectiveness of different booking channels
- **Cancellation Analysis**: Identify patterns in booking cancellations and no-shows

### 4. Predictive Analytics
- **Demand Forecasting**: Predict future booking volumes and revenue
- **Dynamic Pricing**: Recommend optimal pricing strategies
- **Guest Lifetime Value**: Calculate and predict customer value

## Usage

### Quick Start

```python
import pandas as pd
from src.analytics import HospitalityAnalyzer

# Load data
analyzer = HospitalityAnalyzer()
bookings_df = pd.read_csv('data/processed/bookings.csv')

# Calculate key metrics
metrics = analyzer.calculate_kpis(bookings_df)
print(f"ADR: ${metrics['adr']:.2f}")
print(f"Occupancy Rate: {metrics['occupancy_rate']:.1f}%")
print(f"RevPAR: ${metrics['revpar']:.2f}")
```

### Running Analysis Notebooks

1. Start Jupyter Notebook: `jupyter notebook`
2. Navigate to the `notebooks/` directory
3. Run notebooks in sequence for comprehensive analysis

## Key Metrics and KPIs

### Revenue Metrics
- **ADR (Average Daily Rate)**: Average revenue per occupied room
- **RevPAR (Revenue per Available Room)**: Total room revenue divided by available rooms
- **GOPPAR (Gross Operating Profit per Available Room)**: Measure of profitability

### Operational Metrics
- **Occupancy Rate**: Percentage of available rooms occupied
- **Length of Stay**: Average number of nights per booking
- **Booking Lead Time**: Average time between booking and arrival

### Guest Satisfaction
- **Overall Rating**: Average guest rating across all reviews
- **NPS Score**: Net Promoter Score based on guest feedback
- **Repeat Guest Rate**: Percentage of returning customers

## Sample Insights

The analysis typically reveals insights such as:
- Peak booking periods and seasonal trends
- Most profitable room types and rate categories
- Guest satisfaction drivers and improvement opportunities
- Optimal pricing strategies for different market segments
- Channel effectiveness and commission optimization

## Data Sources

Common data sources for hospitality analysis include:
- Property Management Systems (PMS)
- Online Travel Agencies (OTAs)
- Review platforms (TripAdvisor, Google Reviews)
- Revenue management systems
- Customer relationship management (CRM) systems

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/analysis-enhancement`)
3. Commit your changes (`git commit -am 'Add new analysis feature'`)
4. Push to the branch (`git push origin feature/analysis-enhancement`)
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For questions or support, please contact:
- Email: your.email@example.com
- LinkedIn: [Your LinkedIn Profile]
- GitHub Issues: [Project Issues Page]

## Acknowledgments

- Hospitality industry professionals who provided domain expertise
- Open-source community for excellent data analysis tools
- Hotel management companies for sharing anonymized datasets

---

*This analysis framework is designed to provide actionable insights for hospitality professionals to optimize operations, enhance guest satisfaction, and maximize revenue.*
