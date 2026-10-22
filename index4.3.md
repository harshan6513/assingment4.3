
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Marksheet</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 30px;
            background-color: #f4f7fc;
        }

        h1 {
            text-align: center;
            color: #1d3557;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background-color: white;
        }

        caption {
            font-size: 22px;
            font-weight: bold;
            padding: 15px;
            color: #1d3557;
        }

        th, td {
            border: 1px solid #555;
            padding: 12px;
            text-align: center;
        }

        thead {
            background-color: #1d3557;
            color: white;
        }

        tbody tr:nth-child(even) {
            background-color: #eaf2f8;
        }

        tfoot {
            background-color: #d8e8dc;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <h1>Student Marksheet</h1>

    <table>
        <caption>Academic Performance of Students</caption>

        <thead>
            <tr>
                <th rowspan="2">Roll No.</th>
                <th rowspan="2">Student Name</th>
                <th colspan="3">Subject Marks</th>
                <th rowspan="2">Total (300)</th>
                <th rowspan="2">Average</th>
            </tr>
            <tr>
                <th>English</th>
                <th>Mathematics</th>
                <th>Science</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>101</td>
                <td>Rahul</td>
                <td>85</td>
                <td>90</td>
                <td>88</td>
                <td>263</td>
                <td>87.67</td>
            </tr>

            <tr>
                <td>102</td>
                <td>Priya</td>
                <td>92</td>
                <td>95</td>
                <td>91</td>
                <td>278</td>
                <td>92.67</td>
            </tr>

            <tr>
                <td>103</td>
                <td>Amit</td>
                <td>76</td>
                <td>82</td>
                <td>79</td>
                <td>237</td>
                <td>79.00</td>
            </tr>

            <tr>
                <td>104</td>
                <td>Neha</td>
                <td>89</td>
                <td>86</td>
                <td>94</td>
                <td>269</td>
                <td>89.67</td>
            </tr>

            <tr>
                <td>105</td>
                <td>Rohit</td>
                <td>80</td>
                <td>75</td>
                <td>84</td>
                <td>239</td>
                <td>79.67</td>
            </tr>
        </tbody>

        <tfoot>
            <tr>
                <td colspan="2">Class Total</td>
                <td>422</td>
                <td>428</td>
                <td>436</td>
                <td>1286</td>
                <td>85.73</td>
            </tr>
            <tr>
                <td colspan="6">Class Average (per student)</td>
                <td>257.20</td>
            </tr>
        </tfoot>
    </table>

</body>
</html>
