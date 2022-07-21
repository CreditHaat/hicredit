anchor-echosystem-odoo
   **BASE PROJECT : **  
  - *master(branch)* 
  - **Date : 3 Jan 2022**
  
   **SRS : **
   
 - **To add pincode filter for client Upwards**
 - Additonal db field named pincode has been added in **t_upwards_city_state**
 
 - Also below queries are run to rectify the existing city name to match the name with shared updated pincode master excel-->
 
 
 - UPDATE *t_upwards_city_state* SET city = 'Vadodara' WHERE id = 5119;
 - UPDATE *t_upwards_city_state* SET city = 'Noida' WHERE id = 5129;
 - UPDATE *t_upwards_city_state* SET city = 'K.V.Rangareddy' WHERE id = 5135;
 - UPDATE *t_upwards_city_state* SET city = 'Bengaluru' WHERE id = 5136;
 - UPDATE *t_upwards_city_state* SET city = 'Belagavi' WHERE id = 5140;
 - UPDATE *t_upwards_city_state* SET city = 'Tiruppur' WHERE id = 5146;
 - UPDATE *t_upwards_city_state* SET city = 'Tiruchirappalli' WHERE id = 5147;
 - UPDATE *t_upwards_city_state* SET city = 'Indore' WHERE id = 5154;
 - UPDATE *t_upwards_city_state* SET city = 'Bhubaneswar' WHERE id = 5158;
 - UPDATE *t_upwards_city_state* SET city = 'Gandhi Nagar' WHERE id = 5120;
 
 
 -  **Against below city name** -->
 -  Baroda
 - Gujarat
 - Gandhinagar
 - Delhi
 - Greater Noida
 - Ranga Reddy
 - Bangalore
 - Belgaum / Belagavi
 - Tirupur
 - Trichy
 - Indore (including Dhar & Mhow)
 - Bhuwaneshwar