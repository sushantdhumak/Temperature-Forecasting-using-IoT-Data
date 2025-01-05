---
### **Temperature Forecasting using IoT Data**
---
#### **Brief Description**

This dataset contains the temperature readings from IOT devices installed outside and inside of an anonymous Room (say - admin room). The device was in the alpha testing phase. So, It was uninstalled or shut off several times during the entire reading period ( 28-07-2018 to 08-12-2018) which resulted in random interval recordings and few mis-readings (outliers)

Dataset Link:
https://www.kaggle.com/datasets/atulanandjha/temperature-readings-iot-devices?resource=download

---

#### **Variable Information**

**id** : unique IDs for each reading

**room_id/id** : room id in which device was installed (inside and/or outside) -> currently 'admin room' only for example purpose.

**noted_date** : date and time of reading

**temp** : temperature readings

**out/in** : whether reading was taken from device installed inside or outside of room?

---

#### **Some interesting questions to answer**

1. What was the max and min temperature?

2. How outside temperature was related to inside temperature?

3. What was the variance of temperature for inside and outside room temperature?

4. Which was the hottest/coolest month?

5. Can we use Time Series Forecast algo to predict the next scenario?
