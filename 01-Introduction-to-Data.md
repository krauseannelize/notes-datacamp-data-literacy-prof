# Introduction to Data

Gain an introduction to data. Learn the basics of data types and structures, the DIKW framework, data ethics and more.

## Table of Contents

1. [Data basics](#data-basics)
   - [Structured vs unstructured](#structured-vs-unstructured)
   - [Quantitative vs qualitative](#quantitative-vs-qualitative)
   - [Data context](#data-context)
   - [Value of data](#value-of-data)
   - [Data growth](#data-growth)
2. [Data wisdom](#data-wisdom)
   - [The DIKW pyramid](#the-dikw-pyramid)
   - [Data in decision making](#data-in-decision-making)
   - [Data as a resource](#data-as-a-resource)
3. [Data in-depth](#data-in-depth)
   - [Data ethics and privacy](#data-ethics-and-privacy)
   - [Data life cycle](#data-life-cycle)
   - [Common data mistakes](#common-data-mistakes)

---

## Data basics

> Data is derived from the Latin word *datum*, which means fact

![Data Everywhere](/images/data-everywhere.png 'Data Everywhere')

---

### Structured vs unstructured

There are two main formats of data:

- ***Structured data***
  - Organized, easy to manage
  - Tabular format
  - Predefined structure
  - Text and numbers
- ***Unstructured data***
  - Unorganized, difficult to manage
  - No specific format
  - No predefined structure
  - Text, images, audio, and/or video.

![Structured and Unstructured Data](/images/data-structured-unstructured.png 'Structured and Unstructured Data')

---

### Quantitative vs qualitative

Another important aspect of data is whether it is:

- ***Quantitative***
  - Also called numerical data
  - Count, measure, represent with numbers
- ***Qualitative***
  - Also called categorical data
  - Group into categories.

---

### Data context

Context is crucial for data to have meaning. ***Data context*** refers to the information that provides meaning to data, also called the metadata. It includes the characteristics of the data, such as the time frame in which it was collected, or its location and source.

---

### Value of data

We all use data in our daily lives for managing finances, planning activities, and tracking health. Organizations, including governmental and non-profit, use data to address various challenges.

| Area | Value |
| --- | --- |
| **Organizations** | Support business objectives by improving decision making: profitability; social good; research; customer satisfaction |
| **Healthcare** | Detect and prevent health problems; turning patient care into precision medicine; advancing healthcare research worldwide |
| **Supply Chain** | Optimize processes like inventory management; do demand forecasting |
| **Education** | Improve course design; identify struggle areas; personalize learning experience |

Leveraging unique organizational data sets businesses apart from competitors. Effective data utilization helps make informed decisions instead of relying on gut feelings.

---

### Data growth

The volume of data has grown exponentially, and as data volume increases, data storage methods evolve. As business operations grow more complex, the volume of generated and stored data increases.

---

[back to top](#introduction-to-data)

---

## Data wisdom

With so much data being generated every day, it is vital that we employ a mental model to simplify our understanding and focus our attention on uncovering value.

---

### The DIKW pyramid

One such mental model is the DIKW (Data, Information, Knowledge, Wisdom) pyramid.

![DIKW Pyramid](/images/dikw-pyramid.jpg 'DIKW Pyramid')

- ***Data***
  - A collection of raw data in the form of measurements and observations
  - It is unorganized and unprocessed
  - It does not have any meaning yet
- ***Information***
  - The raw data is placed into context
  - Context is typically given by organizing and aggregating data
- ***Knowledge***
  - Combine information to make connections to learn and gain meaning
  - Typically done by detecting patterns, making generalizations or predictions
- ***Wisdom***
  - Applying knowledge to act proactively and guide decisions effectively
  - Insights bridge the gap between knowledge and action, leading to better predictions and understanding

---

### Data in decision-making

The decision making is the process of making the right choices at the right time. For many decisions, employing data can help make a tough choice clearer. Data driven decision making is a five-step process:

1. ***Asking the right questions***
   - Outline exactly what you are looking to answer
   - A well-defined question prevents scope creep
   - Ensure success throughout the rest of the process
2. ***Collecting the right data***
   - With a clear question, the search for the right data begins
   - Data can exist in various forms and locations
   - Being deliberate about sourcing data and considering its future analysis can save time in the data preparation phase
3. ***Preparing data***
   - Involves converting low-quality data into higher quality through manipulation
   - Arrange data into expected structure for analysis
   - Sometimes this is the most time consuming step with 80% of time spent on data cleaning
4. ***Analyzing data***
   - Transforms data into actionable insights using tools like Python, R, Tableau, Power BI, Excel, and Google Sheets.
   - These tools help find insights necessary for decision-making
5. ***Making decisions***
   - Interpreting the analysis results to make data-driven decisions
   - Balance outcomes with personal knowledge and experiences.
   - The process is iterative, allowing for continuous improvements based on observed outcomes.

---

### Data as a resource

Data is often too large to work with effectively in its raw form. Even simple tasks can involve hundreds or thousands of records, while complex tasks may involve millions or billions. Summarizing data into smaller pieces is essential for making informed decisions. ***Aggregations*** help translate raw data into more understandable forms. Common aggregations that make large datasets more usable and focus on specific attributes include:

- averages (mean)
- totals (sums)
- minimums and maximums
- modes

Aggregations appear in many ways within organizations and understanding how these aggregations are created is extremely helpful for many investigations:

- Metrics
- Benchmarks
- Key Performance Indicators (KPIs)

Being curious about data aggregations helps unlock their value. Tracing a report's origin or uncovering the assumptions behind a KPI can provide deeper insights. Understanding why benchmarks are set the way they are is important.

Data flow in organizations can be complex, involving multiple source systems and processing stages. Data management aims to streamline these processes. Common domains in data management include data governance, data quality, data privacy, and data security. Each domain in data management ensures data is utilized effectively and responsibly. Data Governance focuses on consistency and trustworthiness, Data Quality on accuracy and completeness, and Data Privacy and Security on access and protection.

---

[back to top](#introduction-to-data)

---

## Data in-depth

Data can drive impactful decisions but comes with responsibilities.

---

### Data ethics and privacy

Data ethics ensure ethical collection, storage, and use of data to protect customers and avoid legal issues. The five principles of data ethics:

- ***Permission*** for data collection
  - Ask before collecting
  - Users are in control of their data
- ***Transparency*** about the plan
  - Be transparent of how you plant to use, store, and collect data
  - Lack of transparency may lead to reputation and legal damage
- ***Privacy*** of data
  - Refers to secluding yourself
  - Personal Identifiable Information (PII) must remain confidential
  - Privacy protection:
    - Strong passwords
    - Up-to-date operating systems
    - Cautionary internet browsing
  - Prevent data breaches:
    - Limit sharing sensitive data
    - Pseudo-data anonymization
- Good ***intensions***
  - Data is collected for the right reasons
  - Questions yourself about the reasons you collect data
- Consider the ***outcome***
  - Are there consequences of your actions?
  - Protecting vulnerable populations

---

### Data life cycle

The Data Life Cycle is a framework for regulating data from collection to use, analysis, and disposal. It ensures responsible data management, helps identify improvement areas, and enhances operational efficiency. Proper handling and leveraging of data are crucial for organizations and researchers.

![Data Life Cycle](/images/data-life-cycle.png 'Data Life Cycle')

Phases of the data life cycle:

1. ***Plan and Collect***
   - Prepare a business question that answers the need of your stakeholders
   - Decide on the type of required data, how and who will be responsible for managing the data, and how to achieve the most effective results
   - Do you need to collect or create data?
2. ***Store and Manage***
   - Data needs to be stored in databases or data warehouses
   - Easily accessible by the right person
   - Can be properly managed over time
   - Removal of PII
3. ***Clean and Process***
   - Formatting data
   - Dealing with missing values or errors
   - Transforming data into a more usable form
4. ***Analyze and Visualize***
   - Analyzing raw data to get new meaningful insights
   - Data is easier to interpret when visualized
   - Various methods are used to analyze and visualize data
5. ***Share***
   - Successfully communicating your results
   - Publishing dashboards, reports, or papers, presenting findings at conferences, or making datasets available
6. ***Archive or Destroy***
   - Decide if data should be archived or destroyed
   - Data archiving:
     - backing up data,
     - maintaining proper documentation
     - digitizing
   - Data destruction:
     - Rarely
     - Protecting private information
     - Free up resources

---

### Common data mistakes

Common mistakes with data include:

1. ***Not clearly defining the problem***
   - Vague questions like "Did you buy anything in the last month?" don't provide actionable insights
   - Specific questions like "Where did you make your last purchase?" yield better data
   - Without a clear question, you risk inappropriate data collection and analysis, and incorrect conclusions
2. ***Insufficient or wrong data***
   - Collecting data that isn't representative of the target audience - data bias
   - Wrong data doesn't allow you to answer the research question
   - Proper cleaning and processing before analysis
3. ***Lack of appropriate analysis***
   - Jumping to conclusions without proper analysis
   - Lack of context may lead to misinterpreting the results
   - Incorrect aggregations or calculations
   - Confusing correlation with causation
4. ***Ineffective communication of results***
   - Most valuable part of the data life cycle
   - Could lead to misunderstandings or incorrect conclusions
   - Ineffective communication:
     - too technical
     - cherry-picking data points
     - unclear visualization

---

[back to top](#introduction-to-data) or continue to next course: [Communicating Data Insights](/02-Communicating-Data-Insights.md)
