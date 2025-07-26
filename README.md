# Big Data Processing and Analytics - Laboratory Exercises

This repository contains laboratory exercises for the **Big Data Processing and Analytics** course at **Politecnico di Torino**.

## Course Information

- **University**: Politecnico di Torino
- **Course**: Big Data Processing and Analytics
- **Academic Year**: 2024-2025
- **Technologies**: Apache Spark, PySpark, Spark SQL, Spark MLlib

## Laboratory Overview

### Lab 5: Word Frequency Analysis
- **Technologies**: Apache Spark RDD, DataFrame APIs
- **Objective**: Analyze word frequencies in text files
- **Key Concepts**: Text processing, filtering, aggregations, statistical analysis

### Lab 6: Amazon Product Co-Review Analysis
- **Technologies**: Spark DataFrame, aggregations
- **Objective**: Find frequently co-reviewed product pairs
- **Key Concepts**: Join operations, grouping, ranking

### Lab 7: Barcelona Bike Sharing Station Criticality
- **Technologies**: Spark DataFrame, date/time functions
- **Objective**: Identify critical timeslots for bike sharing stations
- **Key Concepts**: Time series analysis, geospatial data, KML output

### Lab 8: Bike Sharing Analysis with Spark SQL
- **Technologies**: Spark SQL, DataFrame API comparison
- **Objective**: Implement Lab 7 analysis using SQL queries
- **Key Concepts**: SQL vs DataFrame APIs, query optimization, data pipelines

### Lab 9: Machine Learning Classification
- **Technologies**: Spark MLlib, classification algorithms
- **Objective**: Binary classification of Amazon review usefulness
- **Key Concepts**: ML pipelines, feature engineering, text processing, model evaluation

## Technologies Used

- **Apache Spark**: Distributed computing framework
- **PySpark**: Python API for Spark
- **Spark SQL**: SQL interface for Spark
- **Spark MLlib**: Machine learning library
- **Jupyter Notebooks**: Interactive development environment

## Key Features Implemented

### Data Processing
- Large-scale data filtering and cleaning
- Complex joins and aggregations
- Time series and geospatial analysis
- Text processing and tokenization

### Machine Learning
- Binary classification models
- Feature engineering and selection
- Text-based features (TF-IDF)
- Model evaluation and comparison
- Pipeline creation and optimization

### Algorithms and Techniques
- Decision Trees
- Logistic Regression
- Text vectorization (HashingTF, IDF)
- Cross-validation and evaluation metrics

## Getting Started

### Prerequisites
- Apache Spark 3.x
- Python 3.7+
- Jupyter Notebook
- PySpark

### Setup
1. Clone this repository
2. Ensure Spark is properly configured
3. Install required Python packages:
   ```bash
   pip install pyspark jupyter notebook
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

### Running the Labs
Each lab contains:
- **PDF instructions**: Detailed requirements and specifications
- **Sample data**: Small datasets for testing
- **Jupyter notebooks**: Complete implementations

To run a lab:
1. Open the corresponding `.ipynb` file
2. Ensure the sample data paths are correct
3. Execute cells sequentially
4. Modify paths for production datasets when available

## Sample Data

This repository includes small sample datasets for testing purposes. For full-scale analysis, the labs are designed to work with larger datasets typically stored in HDFS or distributed file systems.

### Data Sources
- **Text files**: For word frequency analysis
- **Amazon reviews**: Product review datasets
- **Barcelona bike sharing**: Historical station usage data

## Results and Outputs

Each lab generates different types of outputs:
- **CSV files**: Processed results and rankings
- **KML files**: Geospatial visualizations
- **Model metrics**: Classification performance reports
- **Visualizations**: Data analysis charts and graphs

## Performance Considerations

The implementations are optimized for:
- **Scalability**: Designed to handle large datasets
- **Efficiency**: Proper use of Spark transformations and actions
- **Memory management**: Appropriate caching and partitioning
- **Best practices**: Following Spark optimization guidelines

## Learning Objectives

Through these labs, students learn:
- Big data processing concepts and techniques
- Distributed computing with Apache Spark
- SQL and DataFrame operations at scale
- Machine learning pipeline development
- Performance optimization strategies
- Real-world data analysis workflows

## Academic Context

These exercises are part of the curriculum for understanding:
- Modern big data technologies
- Scalable analytics solutions
- Industry-standard tools and practices
- Distributed system design principles

## License

This repository is for educational purposes as part of the Big Data Processing and Analytics course at Politecnico di Torino.

## Acknowledgments

- **Politecnico di Torino** - Course materials and structure
- **Apache Software Foundation** - Spark framework
- **Course instructors** - Guidance and requirements specification

---

**Note**: This repository contains academic exercises and should be used in accordance with university policies regarding academic integrity and code sharing.
