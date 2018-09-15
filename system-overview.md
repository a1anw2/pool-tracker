## System Overview

We will divorce the hardware away from the main application.   The Raspberry system, will be responsible for taking the photos and positioning the feedback to the table.   It will present a RESTful API for the main application to control.

The Main App will require the endpoint for the Raspberry PI so it can send and receive commands.

```
+--------------------------+                   +------------------+
|                          |                   |                  |
|  Raspberry PI            | <---------------+ |  Main Web App    |
|                          |                   |                  |
|                          |                   |                  |
|                          | +---------------> |                  |
|                          |                   |                  |
+-----+---------------+----+                   +------------------+
      |               |
      |               |
      |               |
 +----v----+    +-----v----+
 |         |    |          |
 | Laser   |    | Camera   |
 |         |    |          |
 +---------+    +----------+
```
