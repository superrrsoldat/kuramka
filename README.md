# Data Visualization Components Package

This package provides a collection of data visualization components for creating charts in JavaScript.

## Installation

Install the package using npm:

```bash
npm install data-visualization-components
```

## Usage

1. Require the package in your Node.js application:

```javascript
const { createBarChart, createLineChart, createPieChart } = require('data-visualization-components');
```

2. Use the visualization components in your code:

```javascript
// Example data for the charts
const data = [10, 20, 30, 40, 50];
const options = {
  // Options for configuring the charts
};

// Create a bar chart
createBarChart(data, options);

// Create a line chart
createLineChart(data, options);

// Create a pie chart
createPieChart(data, options);
```

## Available Functions

### createBarChart(data, options)

Creates a bar chart with the given data and options.

### createLineChart(data, options)

Creates a line chart with the given data and options.

### createPieChart(data, options)

Creates a pie chart with the given data and options.

## License

This package is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
