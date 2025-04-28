![Screenshot 2025-04-28 160824](https://github.com/user-attachments/assets/544a4673-2d07-4fff-8101-109fb8762a70)# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
```
content='''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>System Specifications</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f9;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        table {
            width: 100%;
            max-width: 600px;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: #fff;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        th, td {
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #f2f2f2;
            font-weight: bold;
        }
        td {
            color: #555;
        }
        .section-title {
            font-size: 1.2em;
            margin-top: 20px;
            color: #444;
        }
    </style>
</head>
<body>

    <h1>System Specifications</h1>
    
    <table>
        <tr>
            <th>Device Name</th>
            <td>DESKTOP-MOHHBTU</td>
        </tr>
        <tr>
            <th>Processor</th>
            <td>13th Gen Intel(R) Core(TM) i5-1335U @ 1.30 GHz</td>
        </tr>
        <tr>
            <th>Installed RAM</th>
            <td>16.0 GB (15.7 GB usable)</td>
        </tr>
        <tr>
            <th>Device ID</th>
            <td>15EEA3B2-7EF5-4DEC-903D-577382C3C005</td>
        </tr>
        <tr>
            <th>Product ID</th>
            <td>00342-42709-07179-AAOEM</td>
        </tr>
        <tr>
            <th>System Type</th>
            <td>64-bit operating system, x64-based processor</td>
        </tr>
        <tr>
            <th>Pen and Touch</th>
            <td>No pen or touch input is available for this display</td>
        </tr>
    </table>
    
    <div class="section-title">Additional Information</div>
    <p>The system is equipped with a 13th Gen Intel Core i5 processor, providing a solid balance of power and efficiency for everyday tasks. The 16 GB of RAM ensures smooth multitasking performance, while the 64-bit architecture supports modern applications and games.</p>

</body>
</html>
```


## OUTPUT:


![Screenshot 2025-04-28 160824](https://github.com/user-attachments/assets/be1f51b1-22e5-4769-a6bf-163720e1a35b)
![Screenshot 2025-04-28 160812](https://github.com/user-attachments/assets/ba395ebf-b016-40d3-8f2a-d175f6a6ed54)


## RESULT:
The program for implementing simple webserver is executed successfully.
