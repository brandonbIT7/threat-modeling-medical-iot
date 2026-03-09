# STRIDE Attack Diagram: Insulin Pump

          Attacker (Remote)
                |
                v
+----------------------------+
|   Bluetooth/WiFi Interface  | <-- **S**poofing: Fake doctor signal
+----------------------------+
               |
                v
          Insulin Pump
                |
+----------------------------+ <-- **T**ampering: Firmware hack
|   Dosage Controller        | **D**oS: Jam connection
|   (Overdose / Fail)        | 
+----------------------------+
               ^
                |
                **I**nfo Disclosure: Leaked glucose data
