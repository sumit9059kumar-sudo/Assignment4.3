File: marksheet.html
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Marks Table</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f8f9fa; margin: 0; padding: 20px; }
        .table-container { max-width: 850px; margin: auto; background: white; padding: 25px; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        h2 { color: #2c3e50; text-align: center; margin-top: 0; }
        table { width: 100%; border-collapse: collapse; margin-top: 15px; }
        caption { font-size: 1.2rem; font-weight: bold; margin-bottom: 12px; color: #2c3e50; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: center; }
        thead th { background-color: #3498db; color: white; }
        tbody tr:nth-child(even) { background-color: #f9f9f9; }
        tbody tr:hover { background-color: #f1f1f1; }
        tfoot td { font-weight: bold; background-color: #e9ecef; }
        .student-name { text-align: left; }
    </style>
</head>
<body>

    <div class="table-container">
        <h2>Semester Examination Results</h2>
        
        <table>
            <caption>Student Marks Summary (5 Students & 3 Subjects)</caption>
            
            <!-- Table Header with Rowspan & Colspan -->
            <thead>
                <tr>
                    <th rowspan="2">Student Name</th>
                    <th colspan="3">Subjects</th>
                    <th rowspan="2">Total Marks <br>(Out of 300)</th>
                    <th rowspan="2">Average (%)</th>
                </tr>
                <tr>
                    <th>Mathematics</th>
                    <th>Science</th>
                    <th>English</th>
                </tr>
            </thead>

            <!-- Table Body with 5 Students Data -->
            <tbody>
                <tr>
                    <td class="student-name">Alice Johnson</td>
                    <td>85</td>
                    <td>90</td>
                    <td>88</td>
                    <td>263</td>
                    <td>87.6%</td>
                </tr>
                <tr>
                    <td class="student-name">Bob Smith</td>
                    <td>78</td>
                    <td>82</td>
                    <td>80</td>
                    <td>240</td>
                    <td>80.0%</td>
                </tr>
                <tr>
                    <td class="student-name">Charlie Brown</td>
                    <td>92</td>
                    <td>95</td>
                    <td>91</td>
                    <td>278</td>
                    <td>92.6%</td>
                </tr>
                <tr>
                    <td class="student-name">Diana Prince</td>
                    <td>74</td>
                    <td>79</td>
                    <td>85</td>
                    <td>238</td>
                    <td>79.3%</td>
                </tr>
                <tr>
                    <td class="student-name">Ethan Hunt</td>
                    <td>88</td>
                    <td>84</td>
                    <td>89</td>
                    <td>261</td>
                    <td>87.0%</td>
                </tr>
            </tbody>

            <!-- Table Footer with Class Totals & Colspan -->
            <tfoot>
                <tr>
                    <td colspan="4" style="text-align: right;">Class Average Score:</td>
                    <td colspan="2">256 Marks (85.3%)</td>
                </tr>
            </tfoot>
        </table>
    </div>

</body>
</html>
Requirements Checklist for Submission:
File Name: Saved as marksheet.html.

Data Coverage: Includes records for 5 students and 3 subjects (Mathematics, Science, English).

Table Structure: Uses proper <table>, <tr>, <th>, and <td> elements.

Semantic Sections: Neatly organized using <thead>, <tbody>, and <tfoot>.

Caption: Added a title to the table using the <caption> tag.

Totals/Averages: Included class summary metrics in the footer.

Colspan & Rowspan: Utilized rowspan for multi-row headers (Student Name, Total Marks, Average) and colspan to merge columns cleanly in the footer.