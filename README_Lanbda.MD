Server Less AWS lambda
No need resourses
Provide code and manage services
Mobile to Iot Application are use AWS lambda 
Phot0 -->  Store S3 --> Lambda [will help to code it] --> get the photo on web/mobile
Serverless computing == Lambda
it provide the customised services
Customer nedds, no need code
oumatically take it

serverless computing
event drivwn execution [use different pro-lang]
wide language support
pay-per-use-pricing
auto-scaling
integration with aws services also

Real time data processing
serverless web application

lambda - Create a Function- fun name-Runtime -python - create function- layers-see the code - Deploy [left side]- Layers- add layer- AWS Layer [x86_64 - version 19- add-test - event name [myEvent]- save- - Invoke- - See Output- add triger- selet sourse api gateway- create new api-HTTP API -Security - Open- add-click api gateway - get URL[API endpoint] -- right click new tab- Get the output- terminate - and - delete - free your aws - thank you


----------------------------------------------------------------
# AWS Lambda:

---

### **Serverless AWS Lambda — Step by Step**

1. **Serverless AWS Lambda**

   * No need for servers or resources.
   * You only provide the code — AWS manages everything.
   * Used for **mobile to IoT applications**.
   * Example flow:
     **Photo → Store in S3 → Lambda (executes code) → Get photo on web/mobile.**

2. **Serverless Computing = AWS Lambda**

   * Provides customized services based on customer needs.
   * No need to manage servers or write complex infrastructure code.
   * Automatically handles execution and scaling.

3. **Key Features**

   * **Event-driven execution** (triggers from various AWS services).
   * **Supports multiple programming languages.**
   * **Pay-per-use pricing** — only pay for the code execution time.
   * **Automatic scaling.**
   * **Integration** with other AWS services (like S3, DynamoDB, API Gateway, etc.).

4. **Use Cases**

   * Real-time data processing.
   * Serverless web applications.

---

### **AWS Lambda Implementation Steps**

1. Go to **AWS Lambda** → click **Create Function**
2. Enter **Function name**
3. Choose **Runtime** → Python
4. Click **Create function**
5. Open the function → go to **Code** section
6. Deploy your code using **Deploy** (left side)
7. Go to **Layers** → **Add layer**

   * Choose **AWS Layer**
   * Architecture: `x86_64`
   * Version: 19
   * Click **Add**
8. Go to **Test** → create a new event

   * Event name: `myEvent`
   * Click **Save**
   * Click **Invoke**
   * See the **output** in the console
9. Add a **Trigger**

   * Select **Source: API Gateway**
   * Create new API → **HTTP API**
   * Security: **Open**
   * Add trigger
10. Click **API Gateway** link → get the **API endpoint URL**
11. Right-click → open in new tab → get the **output**
12. After testing → **Terminate** and **Delete** resources to avoid charges
13. ✅ Done — AWS Lambda implemented successfully
14. **Thank you!**

---