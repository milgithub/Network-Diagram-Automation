# Network-Diagram-Automation
I've created a Python script which will be useful for automating Network Diagram tasks. Please make sure to correct the path mentioned in the script to match your actual path. 

You should have excel file as below: (kindly note, it is just for an example, and you can use it for any visio stencils for real shape, note, you need to mention stencil (master) name correctly in the excel sheet.

| Local Device Name | Local Device        | Local Port | Remote Device Name | Remote Device        | Remote Port |
|-------------------|---------------------|------------|-------------------|---------------------|------------|
| ISP1              | Cloud               | 1          | CE1               | Router              | 1          |
| ISP2              | Cloud               | 1          | CE2               | Router              | 1          |
| MX01              | MX250-HW Front      | 1          | CE1               | Router              | 2          |
| MX01              | MX250-HW Front      | 2          | CE2               | Router              | 2          |
| MX02              | MX250-HW Front      | 1          | CE1               | Router              | 3          |
| MX02              | MX250-HW Front      | 2          | CE2               | Router              | 3          |
| MX01              | MX250-HW Front      | 3          | DS01              | MS410-16-HW Front   | 1          |
| MX02              | MX250-HW Front      | 3          | DS02              | MS410-16-HW Front   | 1          |
| DS01              | MS410-16-HW Front   | 16         | DS02              | MS225-48-HW Front   | 16         |
| DS01              | MS410-16-HW Front   | 12         | MS01              | MS225-48-HW Front   | 48         |
| DS01              | MS410-16-HW Front   | 13         | MS03              | MS225-48-HW Front   | 48         |
| DS02              | MS410-16-HW Front   | 14         | MS02              | MS225-48-HW Front   | 48         |
| DS02              | MS410-16-HW Front   | 15         | MS04              | MS225-48-HW Front   | 48         |
| MS01              | MS225-48-HW Front   | 1          | MR01              | MR42E-HW Top         | 1          |
| MS02              | MS225-48-HW Front   | 1          | MR02              | MR42E-HW Top         | 1          |
| MS03              | MS225-48-HW Front   | 1          | MR03              | MR42E-HW Top         | 1          |
| MS04              | MS225-48-HW Front   | 1          | MR04              | MR42E-HW Top         | 1          |
| MS04              | MS225-48-HW Front   | 2          | MR05              | MR66-HW Front        | 1          |


