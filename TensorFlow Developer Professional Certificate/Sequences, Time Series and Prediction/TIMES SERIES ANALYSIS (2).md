[→ Open in Slid](https://slid.cc/docs/b8d05fe11211434989a4e22397bc2b54)


---


**MOVING AVERAGE**

[![TIMES SERIES ANALYSIS image](https://slid-users-assets-v1-mumbai.s3.ap-south-1.amazonaws.com/public/capture_images/b8d05fe11211434989a4e22397bc2b54/c6427488-e98b-40c6-9c22-8cb5ebeb9bd0.png)](https://slid.cc/vdocs/b8d05fe11211434989a4e22397bc2b54?v=15e2cbc9817d498ea243560420b370e6&start=4.808915)


SIMPLEST WAY TO FORCASTING IS **MOVING AVERAGE.** Nicly eleminates lots of the noise and gives us a curve roughly emulaing the original series but **does not anticipate trend or seasonality.**

---


**DIFFERENCING** Removing seasonality from the time series. Instead of studying time series we study the difference between the value at time T and value at an earlier period.

[![TIMES SERIES ANALYSIS image](https://slid-users-assets-v1-mumbai.s3.ap-south-1.amazonaws.com/public/capture_images/b8d05fe11211434989a4e22397bc2b54/8deb5601-681c-4150-bc9f-5559a3e8eab5.png)](https://slid.cc/vdocs/b8d05fe11211434989a4e22397bc2b54?v=15e2cbc9817d498ea243560420b370e6&start=75.308962)







[![TIMES SERIES ANALYSIS image](https://slid-users-assets-v1-mumbai.s3.ap-south-1.amazonaws.com/public/capture_images/b8d05fe11211434989a4e22397bc2b54/f6aa30e4-9ba8-4328-bab3-615db033be0e.png)](https://slid.cc/vdocs/b8d05fe11211434989a4e22397bc2b54?v=15e2cbc9817d498ea243560420b370e6&start=83.716675)


Then use moving average to forcaste this time series. But these are just forcaste for the difference time series not original time series. To get final forcaste we just need to add back the value at time T minus 365.

[![TIMES SERIES ANALYSIS image](https://slid-users-assets-v1-mumbai.s3.ap-south-1.amazonaws.com/public/capture_images/b8d05fe11211434989a4e22397bc2b54/939058fa-a176-41bd-84b8-eb4db0397801.png)](https://slid.cc/vdocs/b8d05fe11211434989a4e22397bc2b54?v=15e2cbc9817d498ea243560420b370e6&start=100.314519)


We can imrpove these forcasts by removing the past noise using a moving average on that

[![TIMES SERIES ANALYSIS image](https://slid-users-assets-v1-mumbai.s3.ap-south-1.amazonaws.com/public/capture_images/b8d05fe11211434989a4e22397bc2b54/ddb42407-aabb-46ec-af3e-63e90e04ed6a.png)](https://slid.cc/vdocs/b8d05fe11211434989a4e22397bc2b54?v=15e2cbc9817d498ea243560420b370e6&start=134.797091)


After doing that we get much smoother forecasts



