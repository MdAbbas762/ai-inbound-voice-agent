# 🎙️ AI Voice Receptionist & CRM Automation

An inbound AI voice receptionist built for **Affordable Modular Buildings (AMB)** to handle customer calls, identify caller needs, collect structured project information, manage CRM records, book appointments, trigger follow-up workflows, and transfer callers to human staff when required.

The system connects **Vapi**, **GoHighLevel**, **Twilio**, **OpenAI**, **Deepgram**, **ElevenLabs**, and REST APIs into a complete inbound customer-handling workflow.

![Vapi](https://img.shields.io/badge/Vapi-Voice_AI-111827?style=flat-square)
![GoHighLevel](https://img.shields.io/badge/GoHighLevel-CRM_%26_Automation-2563EB?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--5-111827?style=flat-square)
![Deepgram](https://img.shields.io/badge/Deepgram-Nova_3-2563EB?style=flat-square)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-Voice_AI-111827?style=flat-square)
![REST API](https://img.shields.io/badge/REST-API-2563EB?style=flat-square)

---

## 📌 Project Overview

Affordable Modular Buildings required an inbound voice system capable of handling different customer enquiries without relying on one generic conversation flow.

The assistant needed to understand who was calling, collect the right information for that customer type, interact with GoHighLevel, perform actions such as contact management and appointment booking, and involve human staff whenever the situation required it.

The final system handles four main caller journeys:

- **New Residential Customers**
- **Commercial Customers**
- **Existing Clients**
- **Factory Tour Enquiries**

General business questions can also be answered using approved information without treating them as a separate customer journey.

---

## 🎯 Business Problem

AMB receives calls from customers with very different needs.

A residential lead may need to review the catalogue, discuss building requirements, and book a phone consultation. A commercial customer needs a different qualification process. Existing clients may need their Project Manager, while factory-tour enquiries require their own booking flow.

The business therefore needed a system that could:

- understand caller intent,
- follow the correct process for each customer type,
- collect structured customer and project data,
- avoid asking irrelevant questions,
- search, create, and update CRM contacts,
- check actual appointment availability,
- book the correct appointment type,
- trigger follow-up workflows,
- route commercial enquiries,
- transfer existing clients when required,
- and avoid giving unconfirmed information.

The objective was not simply to create a voice chatbot. The assistant needed to become part of the company's real customer-handling workflow.

---

## 💡 Solution

The solution combines **GoHighLevel telephony and CRM automation with a Vapi AI voice assistant**.

The process starts when a customer calls the AMB business number. Human staff receive the first opportunity to answer. If the call is unanswered, the GoHighLevel call-forwarding workflow sends the call to the AI receptionist.

The assistant then:

1. Understands why the customer is calling.
2. Identifies the relevant caller journey.
3. Follows the appropriate conversation flow.
4. Collects the required customer and project information.
5. Uses structured tools to interact with GoHighLevel.
6. Performs the required CRM, booking, routing, or transfer action.
7. Gives the customer a clear next step.

This connects the conversation directly with real business operations instead of leaving the information only inside a call transcript.