# Email Marketing Data Analysis Project
Using PowerBI , DAX and SQL
<img width="1435" height="808" alt="Screenshot 2025-12-26 131144" src="https://github.com/user-attachments/assets/7d443f3a-6905-4548-9b8b-cba78655d686" />


# Problem Statement
Email unsubscribe rates continue to rise as subscribers disengage from repeated marketing campaigns. This problem occurs across different campaign types, regions, devices, and sending times, making it difficult to pinpoint the drivers of churn. Identifying when and where unsubscribes occur—and why users opt out—is critical to improving engagement, reducing churn, and maximizing email marketing effectiveness.

# Overall Insights
1. Unsubscribe rate is critically high (49.84%) → this is the biggest red flag.
2. CTR (0.30%) is very low, despite a moderate Open Rate (0.60%).
3. Mobile and tablet users unsubscribe slightly more than desktop, indicating possible UX or content issues.
4. Newsletters drive the most opens but also the most unsubscribes, suggesting content fatigue.
5. Emails sent between 9–12 and 15–18 perform best in opens but also increase unsubscribes if overused.
6. Asia leads in total unsubscribes, requiring regional strategy adjustments.

Overall: People open your emails, but many decide to leave afterward. This strongly suggests a content relevance and expectation mismatch, not a deliverability problem.

# Data
The dataset was cleaned by removing duplicates, addressing missing values, and standardizing formats to ensure reliable and accurate analysis.

<img width="526" height="873" alt="Screenshot 2025-12-26 131615" src="https://github.com/user-attachments/assets/f46276fa-ca9f-40cd-9d6e-2f21ffcb05e6" />
<img width="545" height="809" alt="Screenshot 2025-12-26 131541" src="https://github.com/user-attachments/assets/6de9942a-0bd0-424d-a456-dddca66c39c7" />
<img width="681" height="753" alt="Screenshot 2025-12-26 131519" src="https://github.com/user-attachments/assets/6cce5c83-1c9e-4727-9e82-6344d31df5ff" />
<img width="730" height="506" alt="Screenshot 2025-12-26 131504" src="https://github.com/user-attachments/assets/703d525e-90e7-4284-916d-e9b685eaa058" />
<img width="531" height="507" alt="Screenshot 2025-12-26 131451" src="https://github.com/user-attachments/assets/f65e4b9d-fd61-4154-973b-f769327eac89" />

# Data Model 
This data model connects campaign, user, and engagement data to analyze email marketing performance and unsubscribe behavior. Campaign details and performance metrics are linked with user-level engagement data to track opens, clicks, and unsubscribes across different categories and send times. User demographics such as region and device type enable deeper insights into engagement patterns and churn drivers.
<img width="1319" height="799" alt="Screenshot 2025-12-26 131053" src="https://github.com/user-attachments/assets/9994aa10-bb2c-44b7-babb-3fb33c881a6c" />


# Findings

KPI Analysis

Unsubscribe Rate (49.84%)
The unsubscribe rate is critically high, with nearly half of all users opting out. This far exceeds industry benchmarks, which typically remain below 1% per campaign and under 5% overall. The result indicates potential over-emailing, weak audience segmentation, misaligned content, and overly aggressive promotional strategies, making unsubscribe reduction the top priority.

Click-Through Rate (0.30%)
Despite emails being opened, very few users proceed to click. This suggests ineffective calls-to-action, unclear value propositions, and content that fails to motivate further engagement, particularly on mobile devices.

Open Rate (0.60)
The open rate indicates moderate engagement and suggests that subject lines and sender reputation are effective. However, the combination of high opens, low clicks, and high unsubscribes points to a post-open experience that does not meet user expectations.


Device Insights
Unsubscribe rates are consistently high across all devices, with mobile users showing the highest rate (50.41%), followed by tablet (49.88%) and desktop (49.19%). This pattern suggests mobile usability issues such as long content, poor layout, and difficult-to-interact elements. Email opens are evenly distributed across devices, indicating that a mobile-first, responsive design strategy is essential.

Time-Based Performance
Emails sent between 10:00–12:00 and 15:00–18:00 generate the highest open rates, confirming effective send-time targeting. However, these same time windows also experience elevated unsubscribe activity, indicating that while timing is optimized, content quality and relevance are insufficient to sustain engagement.

Category Performance
Newsletters generate the highest number of opens but also the highest number of unsubscribes, indicating content fatigue or excessive frequency. In contrast, re-engagement campaigns show the most favorable balance between opens and unsubscribes, suggesting that targeted and behavior-driven messaging is more effective. This highlights the need to redesign newsletter strategy while expanding successful re-engagement approaches.

# Recomendation

A/B Test Internal Content and CTAs:
Action: Immediately run A/B tests on the body copy, Call-to-Action (CTA) placement, button design, and the clarity of the value proposition inside the email. The current content is failing to deliver on the subject line's promise.
Audit Mobile Experience:
Action: Prioritize checking email rendering and performance on mobile devices. Ensure emails are responsive, fast-loading, and have large, clear CTA buttons.
Investigate Email Frequency/Segmentation:
Action: The extremely high unsubscribe rate suggests either the sending frequency is too high (email fatigue) or the list segmentation is too broad. Implement a preference center allowing users to choose their frequency (daily, weekly, monthly) and content type (newsletter, promotions, etc.).










