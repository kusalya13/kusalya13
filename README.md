# Hi, I'm Kusalya

I studied Physical Science at A/L. I'm interested in electrical engineering and automation, especially how controllers respond when a sensor reading changes or goes missing. I use this profile to share my projects, the tests I ran, and what I learned.

## Tech & Tools

| Area | Tools and practice |
| --- | --- |
| Controller simulation | Excel formulas, state transitions and timing |
| Verification | Expected vs. actual results, boundary tests and fault recovery |
| Currently learning | Python for reading event logs and checking controller behavior |

## Key Projects

### [Thermal Monitor V1](https://github.com/kusalya13/thermal-monitor-controller)

**Temperature controller simulation · Excel**

At 44°C my model can be in Warning or Alarm, depending on whether it has already reached 45°C. Testing that difference helped me understand why hysteresis matters. I also checked how the controller reacts when readings stop and how it recovers when they return.

**Result:** All 10 steps in the combined Excel test matched the expected states. The repository includes the workbook and the test notes.

### Factory Line Auditor · In progress

**Virtual conveyor fault detection · Python**

I'm starting with a rule that checks whether a simulated conveyor reports a jam on time. Next, I want to replay the same event log with 3-second and 5-second timeouts to see how each setting affects false alarms and detection delay.
