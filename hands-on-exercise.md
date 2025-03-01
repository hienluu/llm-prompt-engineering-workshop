## Hands-On Exercises

### Meeting Summary Generation
#### Task
Imagine you have raw, unstructured meeting notes from a weekly team meeting. Your goal is to produce a concise yet comprehensive summary that highlights key decisions, action items, deadlines, and discussion points.

Craft a prompt that instructs the language model to transform these raw notes into a polished meeting summary.

#### Input

```
Meeting Title: Marketing Campaign Strategy Meeting
Date: February 15, 2025
Time: 10:00 AM
Location: Conference Room B
Attendees: Sarah, Chris, Jordan, Maria

Discussion Points:
- Sarah presented the Q1 performance report: website traffic increased by 15%, but conversion rates declined by 2%. Customer feedback also suggested that visual elements in advertising could be improved.
- The team reviewed the current ad targeting strategies. It was noted that the approach could be optimized using newly-acquired customer demographic data.
- Chris raised concerns about the performance of the current ad agency and proposed evaluating alternative service providers.
- Jordan recommended increasing social media ad spend by 10% to boost engagement.
- Maria expressed budget constraints and stressed the importance of a cost-effective strategy, suggesting a detailed review of existing funds.

Action Items:
- Maria will create a revised budget proposal by February 20, 2025.
- Jordan is tasked with scheduling a review meeting with the current ad agency.
- Chris will research and compile a list of alternative ad agencies, with findings due by the end of the week.
- The team agreed to plan a campaign revamp targeted for a March 2025 launch.

Next Meeting:
- Scheduled for February 22, 2025 to review progress and refine the campaign strategy.
```
#### Output
* Part #1:
  * A concise summary highlights key points, key decisions and action items
* Part #2:
  * Analyze potential risks or opportunities
  * Reflects on the team's overall sentiment, morale, or tone
  * Create a creative tagline


### Data Analysis
#### Task
You have a dataset that contains monthly sales figures across different regions. Your task is to extract meaningful insights and suggest appropriate visualizations to present the data effectively.

#### Input
```
Date,Region,Product_Category,Units_Sold,Sales_Amount,Discount_Percentage
2025-01-05,North,Electronics,12,2400,5
2025-01-05,South,Clothing,25,1500,15
2025-01-06,East,Home & Kitchen,30,1800,10
2025-01-07,West,Electronics,18,2000,20
2025-01-08,North,Clothing,40,1600,10
2025-01-09,South,Electronics,15,1800,5
2025-01-10,East,Electronics,10,1200,2
2025-01-11,West,Home & Kitchen,35,2100,12
2025-01-12,North,Home & Kitchen,20,1600,0
2025-01-13,South,Clothing,50,2000,25
2025-01-14,East,Clothing,30,1400,5
2025-01-15,West,Electronics,22,2200,10
2025-01-16,North,Electronics,15,1900,15
2025-01-17,South,Home & Kitchen,40,2400,20
2025-01-18,East,Electronics,12,1300,5
```

#### Output
* Part #1
  * summarize the data
  * key insights along with suggested visualization
  * recommended action based on the insights
* Part #2
  *  Discount impact on revenue per unit
  *  Regional variance in revenue efficiency
  *  Product category trends
  *  Opportunities in Electronics
  *  Sales consistency vs promotional effects

### Developing a Marketing Campaign Idea
#### Task
A company is launching a new line of eco-friendly reusable water bottles. The target audience is urban, environmentally conscious professionals aged 25-40. The campaign should emphasize sustainability and modern design

Write a prompt that instructs the language model to generate multiple creative marketing campaign ideas. Each idea should include:
* A brief description.
* A suggested social media strategy.
* Ideas for engaging the target audience

#### Input
Product Details: Eco-friendly reusable water bottles with a focus on sustainability and modern design

#### Ideas to  consider
* Integration of influencer partnerships
* Inclusion of an interactive online challenge element

Possible outcomes:
* Campaign Idea 1: A sustainability challenge encouraging users to share eco-friendly habits, paired with influencer endorsements.
* Campaign Idea 2: A series of short, engaging videos on social media showcasing modern design and environmental impact, with interactive polls.
* Campaign Idea 3: A collaborative campaign where customers co-create designs for future bottles, integrated with live Q&A sessions from influencers.
