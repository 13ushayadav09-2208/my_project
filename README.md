# my_project
Capstone Project — Delhivery Last-Mile Delay Intelligence Pipeline

**Program:** Artificial Intelligence and Machine Learning Certification Program · E&ICT Academy, IIT Roorkee
**Duration:** 14 days · **Total marks:** 100 · **One deliverable:** a single public GitHub repository (one branch, `main`)

## Scenario

You have joined the regional operations analytics team of **Delhivery**, one of India's largest logistics networks. Every parcel is booked with a promised delivery time (Express 36 hours, Standard 60 hours, Economy 96 hours). The regional operations head has three open problems and no pipeline that answers any of them:

1. **How long will a parcel really take?** Planners need a delivery-hours estimate for each parcel at dispatch time.
2. **Which parcels will miss their promise?** Ops can place a proactive customer call or escalate to a hub manager, but only for parcels flagged *before* they are late. A missed delayed parcel costs more than an unnecessary call.
3. **Which hubs need which playbook?** Each of the 24 hubs is labelled Tier 1, 2 or 3, but nobody has checked whether the label matches how the hub really behaves.

You will answer all three in **one connected repository**. The cleaning and feature code you write in Part A feeds the regression in Part B and the classifier in Part C; the classifier from Part C and the hub segments from Part D are combined by a final scoring script that turns a batch of new parcels into an action list. No later Part may use a number it did not compute itself or receive from an earlier Part.

> **The data is synthetic.** Delhivery's real shipment records are never used. Every row in this brief's dataset is produced by the generator script below; the brand is only the setting for the decisions.

