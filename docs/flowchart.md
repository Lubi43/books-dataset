This flowchart illustrates the core decision logic behind the book filtering system, showing how user inputs transform into personalized recommendations.<br>

```mermaid
flowchart TD
S([CSV dataset import]) --> IN[/"Get user input"/]
IN --> F1@{ shape: processes, label: "Filters" }
F1 --> O1[Title]
F1 --> O2[Author]
F1 --> O3[Rating]
F1 --> O4[Genre]
F1 --> O5[Page count]
F1 --> O6[Year published]
O1 --> F2[Input received?]
O2 --> F2[Input received?]
O3 --> F2[Input received?]
O4 --> F2[Input received?]
O5 --> F2[Input received?]
O6 --> F2[Input received?]
F2 -->|Yes| F3[Apply filters]
F2 -->|No| F4[Show all books]
F3 --> OUT[/"Output book list"/]
F4 --> OUT
OUT --> E([More search options])
E -.-> S1[Top 10 best rated books by genre]
E -.-> S2[Random book]
E -.-> S3[Ten random books from selected genre]
S1 --> I1[User input]
I1 --> OUT2[/"Output book list"/]
S2 ---> OUT3[/"One random book"/]
S3 --> I2[User input]
I2 --> OUT4[/"Output book list"/]
```
Flowchart key:<br>
- **Rectangles**: Process steps <br>
- **Stacked rectangles**: Several processes<br>
- **Parallelogram**: Outputs from searches<br>
- **Ovals**: Start/End points<br>
- **Solid arrows**: Primary workflow path<br>
- **Dashed arrows**: Alternative paths/Optional search <br>