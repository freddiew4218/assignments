
### Problem 1: Simple Table with Antra Logo
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Table</title>
    <style>
        table {
            width: 50%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        .logo {
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="logo">
        <a href="https://antra.net/">
            <img src="https://antra.net/wp-content/uploads/2020/01/cropped-logo-dark.png" alt="Antra Logo" width="200">
        </a>
    </div>
    <table>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
            <th>Header 3</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
            <td>Row 1, Cell 3</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
            <td>Row 2, Cell 3</td>
        </tr>
        <tr>
            <td>Row 3, Cell 1</td>
            <td>Row 3, Cell 2</td>
            <td>Row 3, Cell 3</td>
        </tr>
    </table>
</body>
</html>
```

### Problem 2: Exam Results Table
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exam Results</title>
    <style>
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        thead {
            background-color: #f2f2f2;
        }
        tfoot {
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Student Name</th>
                <th>Math</th>
                <th>Science</th>
                <th>History</th>
                <th>English</th>
                <th>Total</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>90</td>
                <td>85</td>
                <td>88</td>
                <td>92</td>
                <td>355</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>78</td>
                <td>82</td>
                <td>84</td>
                <td>80</td>
                <td>324</td>
            </tr>
            <tr>
                <td>Emily Johnson</td>
                <td>95</td>
                <td>89</td>
                <td>94</td>
                <td>90</td>
                <td>368</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>80</td>
                <td>70</td>
                <td>75</td>
                <td>78</td>
                <td>303</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="4">Average</td>
                <td colspan="2">337.5</td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
```
### Problem 3: Nested Tables
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nested Tables</title>
    <style>
        table {
            width: 70%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        .logo {
            text-align: center;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="logo">
        <a href="https://antra.net/" target="_blank">
            <img src="https://antra.net/wp-content/uploads/2020/01/cropped-logo-dark.png" alt="Antra Logo" width="200">
        </a>
    </div>
    <table>
        <tr>
            <th>Main Header 1</th>
            <th>Main Header 2</th>
        </tr>
        <tr>
            <td>
                <table>
                    <tr>
                        <th>Sub Header 1</th>
                        <th>Sub Header 2</th>
                    </tr>
                    <tr>
                        <td>Sub Data 1</td>
                        <td>Sub Data 2</td>
                    </tr>
                    <tr>
                        <td>Sub Data 3</td>
                        <td>Sub Data 4</td>
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <th>Sub Header 3</th>
                        <th>Sub Header 4</th>
                    </tr>
                    <tr>
                        <td>Sub Data 5</td>
                        <td>Sub Data 6</td>
                    </tr>
                    <tr>
                        <td>Sub Data 7</td>
                        <td>Sub Data 8</td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>
</body>
</html>
```

### Problem 4: Life in Antra
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Life in Antra</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            margin: 20px;
        }
        .header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
        }
        .content {
            margin: 20px 0;
        }
        .image {
            width: 300px;
            height: 200px;
            background-color: #f2f2f2;
            display: inline-block;
            margin: 10px;
            line-height: 200px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Life in Antra</h1>
    </div>
    <div class="container">
        <div class="content">
            <div class="image">Image 1</div>
            <div class="image">Image 2</div>
            <div class="image">Image 3</div>
        </div>
    </div>
</body>
</html>
```

### Problem 5: "Life in Antra" Keyboard

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Life in Antra Keyboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            margin: 20px;
        }
        .header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
        }
        .keyboard {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .key {
            width: 100px;
            height: 50px;
            background-color: #f2f2f2;
            border: 1px solid #ccc;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 5px;
            cursor: pointer;
        }
        .key:hover {
            background-color: #ddd;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Life in Antra</h1>
    </div>
    <div class="container">
        <div class="keyboard">
            <a href="https://example.com" target="_blank"><div class="key">Link 1</div></a>
            <a href="https://example.com" target="_blank"><div class="key">Link 2</div></a>
            <a href="https://example.com" target="_blank"><div class="key">Link 3</div></a>
            <a href="https://example.com" target="_blank"><div class="key">Link 4</div></a>
            <a href="https://example.com" target="_blank"><div class="key">Link 5</div></a>
        </div>
    </div>
</body>
</html>
```
