# Ex.No.4 – Generate the Prompt and Evaluate for Advanced Prompting Techniques

**DATE:** 21/08/26 
**REGISTER NUMBER:** 212223060077  

## Aim

To write the prompt for the following prompt types and compare them with different AI tools and evaluate them using one evaluation method (Rubrics).

- Zero-shot Prompting
- Few-shot Prompting
- Chain of Thought
- Persona Pattern
- Reverse Prompting
- Graph Prompting
- Active Prompting

# Use Case

## Smart Manufacturing using IoT and Embedded Systems

### Scenario

The manufacturing industry is adopting IoT devices and embedded controllers to automate machines, monitor equipment performance, and perform predictive maintenance. The system continuously collects sensor data, enables remote monitoring, reduces downtime, and improves production efficiency.

### Target Audience

- Manufacturing companies
- IoT engineers
- Embedded systems students
- Industrial automation developers
- Researchers

### Main Objectives

- Improve production efficiency by 30%.
- Minimize machinery downtime using predictive maintenance.
- Enable real-time monitoring and remote control.
- Reduce energy consumption through process optimization.

---

# Prompt Design and Evaluation

## 1. Zero-shot Prompting

### Prompt

> Explain how an IoT-based smart manufacturing system improves production efficiency and predictive maintenance.

### Expected AI Response

An IoT-based manufacturing system uses sensors, embedded controllers, and cloud connectivity to collect real-time machine data. The system detects abnormal conditions, predicts equipment failures, schedules maintenance before breakdowns, and optimizes production processes to improve efficiency.

### Observation

The model generates a complete response without being provided with any examples.

---

## 2. Few-shot Prompting

### Prompt

**Example 1**

**Input:** Motor temperature exceeds the safe limit.  
**Output:** Generate an overheating alert and reduce machine speed.

**Example 2**

**Input:** Vibration sensor detects abnormal movement.  
**Output:** Schedule predictive maintenance immediately.

**Now Answer**

**Input:** Power consumption suddenly increases.

### Expected AI Response

Analyze energy usage, identify the affected machine, notify the operator, and optimize the operating parameters to reduce power consumption.

### Observation

Providing examples helps the AI understand the expected response format and improves consistency.

---

## 3. Chain of Thought Prompting

### Prompt

> A manufacturing plant wants to prevent machine failures. Explain step by step how an IoT system performs predictive maintenance.

### Expected AI Response

1. Collect data from temperature, vibration, and current sensors.
2. Transmit the data to the monitoring system.
3. Analyze the sensor readings continuously.
4. Detect abnormal operating conditions.
5. Predict possible equipment failure.
6. Notify the maintenance team.
7. Schedule maintenance before breakdown.
8. Resume normal production after servicing.

### Observation

The response follows a logical sequence, making the reasoning process easier to understand.

---

## 4. Persona Pattern

### Prompt

> You are an experienced industrial automation engineer. Explain how IoT improves smart manufacturing.

### Expected AI Response

As an automation engineer, I use IoT sensors and embedded controllers to monitor machines continuously. Real-time data helps identify faults early, improve production quality, reduce downtime, optimize energy consumption, and enable remote supervision of the manufacturing process.

### Observation

The response reflects the perspective and expertise of an industrial automation professional.

---

## 5. Reverse Prompting

### Prompt

> A factory reduced downtime, improved energy efficiency, monitored machines remotely, and predicted equipment failures successfully. What prompt could have generated this response?

### Expected AI Response

Design an IoT-based smart manufacturing system that performs real-time machine monitoring, predictive maintenance, remote control, and energy optimization to improve production efficiency.

### Observation

The AI infers the original prompt from the desired output.

---

## 6. Graph Prompting

### Prompt

> Represent the workflow of an IoT-based smart manufacturing system as a flow diagram.

### Expected AI Response

```text
Start
   │
   ▼
Collect Sensor Data
   │
   ▼
Monitor Machine Status
   │
   ▼
Analyze Performance
   │
   ▼
Detect Faults
   │
   ▼
Predict Maintenance
   │
   ▼
Optimize Energy Usage
   │
   ▼
Continue Production
   │
   ▼
End
```

### Observation

Graph prompting organizes the information visually, making workflows easier to understand.

---

## 7. Active Prompting

### Prompt

> Determine whether a machine should continue operating after abnormal vibration is detected. If additional information is required, ask follow-up questions before giving the final recommendation.

### Expected AI Response

The AI first asks questions such as:

- What is the vibration level?
- What is the machine temperature?
- Is the motor operating under full load?
- Has this fault occurred previously?
- Is maintenance immediately available?

After receiving the information, it recommends either continuing operation with monitoring or stopping the machine for predictive maintenance.

### Observation

The AI actively gathers missing information before making a decision, improving accuracy.

---

# Outputs for Each Prompting Technique

## 1. Zero-shot Prompting

### Prompt

Explain how an IoT-based smart manufacturing system improves production efficiency and predictive maintenance.

### AI Output

An IoT-based manufacturing system uses sensors, embedded controllers, and cloud platforms to monitor machines continuously. It detects abnormal conditions, predicts failures before they occur, reduces downtime, and improves overall production efficiency through real-time automation.

---

## 2. Few-shot Prompting

### Prompt

**Example 1**

Input: Motor temperature exceeds the safe limit.

Output: Reduce machine speed and send an alert.

**Example 2**

Input: Vibration sensor detects abnormal movement.

Output: Schedule predictive maintenance.

**Now Answer**

Input: Energy consumption increases unexpectedly.

### AI Output

Output: Identify the machine with high power usage, notify the operator, and optimize its operating parameters to reduce energy consumption.

---

## 3. Chain of Thought Prompting

### Prompt

A manufacturing plant wants to prevent machine failures. Explain step by step how an IoT system performs predictive maintenance.

### AI Output

Step 1: Collect sensor data.

Step 2: Transfer data to the monitoring platform.

Step 3: Analyze temperature, vibration, and current values.

Step 4: Detect abnormal machine behavior.

Step 5: Predict possible equipment failure.

Step 6: Generate maintenance alerts.

Step 7: Schedule servicing.

Step 8: Restore normal production.

---

## 4. Persona Pattern

### Prompt

You are an experienced industrial automation engineer. Explain how IoT improves smart manufacturing.

### AI Output

As an industrial automation engineer, I use IoT devices to monitor machine performance in real time. The system predicts failures, reduces maintenance costs, improves production quality, and enables remote control of industrial equipment for efficient manufacturing.

---

## 5. Reverse Prompting

### Prompt

A factory successfully reduced downtime, optimized energy usage, and implemented predictive maintenance. Generate the prompt that could have produced this response.

### AI Output

Design an IoT-based smart manufacturing system that performs predictive maintenance, real-time monitoring, remote machine control, and energy optimization to improve industrial productivity.

---

## 6. Graph Prompting

### Prompt

Represent the workflow of an IoT-based smart manufacturing system as a flow diagram.

### AI Output

```text
Start
  │
  ▼
Collect Sensor Data
  │
  ▼
Monitor Equipment
  │
  ▼
Analyze Data
  │
  ▼
Detect Faults
  │
  ▼
Predict Maintenance
  │
  ▼
Optimize Process
  │
  ▼
Production Continues
```

---

## 7. Active Prompting

### Prompt

Determine whether a machine should continue operating after abnormal vibration is detected. Ask for missing information before giving the recommendation.

### AI Output

Before deciding, I need:

1. Current vibration value.
2. Machine temperature.
3. Operating load.
4. Remaining production time.
5. Previous maintenance history.

Based on the answers:

- If vibration is within the warning range and temperature is normal, continue operation with monitoring.
- If vibration is critical or temperature is high, stop the machine and perform predictive maintenance.

---

# Comparison with Different AI Tools

| Prompt Type | ChatGPT | Google Gemini | Microsoft Copilot |
|---|---|---|---|
| Zero-shot Prompting | Detailed and accurate | Clear explanation | Moderate detail |
| Few-shot Prompting | Learns examples effectively | Good consistency | Adequate |
| Chain of Thought | Well-structured reasoning | Logical explanation | Basic reasoning |
| Persona Pattern | Natural expert response | Professional style | Brief |
| Reverse Prompting | Highly accurate prompt generation | Good | Moderate |
| Graph Prompting | Clear workflow representation | Good flow | Simple diagram |
| Active Prompting | Excellent follow-up questioning | Good clarification | Limited questions |

---

# Evaluation Method – Rubrics

## Evaluation Criteria

| Criteria | Excellent (5) | Good (4) | Average (3) |
|---|---|---|---|
| Reasoning | Logical and complete | Mostly logical | Basic reasoning |
| Correctness | Highly accurate | Minor errors | Some inaccuracies |
| Token Usage | Efficient and concise | Moderate | Slightly verbose |

## Rubrics Scores

| AI Tool | Reasoning | Correctness | Token Usage | Total / 15 |
|---|---:|---:|---:|---:|
| ChatGPT | 5 | 5 | 5 | **15** |
| Google Gemini | 4 | 5 | 4 | **13** |
| Microsoft Copilot | 4 | 4 | 4 | **12** |

---

# Result Analysis

- **ChatGPT** generated the most logical, accurate, and concise responses across all prompting techniques.
- **Google Gemini** produced technically correct responses with good reasoning but occasionally used more tokens.
- **Microsoft Copilot** provided shorter responses suitable for quick understanding but with less detailed reasoning.

---

# Conclusion

This experiment successfully demonstrated the use of advanced prompting techniques for an IoT-based Smart Manufacturing System. Zero-shot prompting generated responses without examples, few-shot prompting improved consistency using sample inputs, chain-of-thought prompting enhanced logical reasoning, persona prompting produced expert-level explanations, reverse prompting inferred the original query from the output, graph prompting presented workflow visually, and active prompting improved decision-making through follow-up questions. Based on the evaluation using reasoning, correctness, and token usage, ChatGPT achieved the highest overall score due to its clear reasoning, high accuracy, and efficient response generation.

---

# Result

Thus, the advanced prompting techniques were implemented successfully, compared across different AI tools, and evaluated using a rubric-based method. The Smart Manufacturing case study demonstrated that selecting the appropriate prompting technique significantly improves AI reasoning, correctness, and response efficiency for industrial automation applications.
