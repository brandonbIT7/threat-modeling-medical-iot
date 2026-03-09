# Risk Mitigation Strategies

## Spoofing
- Require strong device pairing (PIN or certificate)
-  Block unauthenticated remote commands
+------------------------------+
| Bluetooth/WiFi Interface | <-- **S**poofing: Fake doctor signal
+----------------+-------------+
                |
                 v
           Insulin Pump
                 |
+------------------------------+ <-- **T**ampering: Firmware hack
|  Dosage Controller          | **DoS: Jam connection
|  (Overdose / Fail)          |
+------------------------------+
              ^
               |
   **I**nfo Disclosure: Leaked glucose data
