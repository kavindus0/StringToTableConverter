# StringToTableConverter

This Python script converts a string of space-separated data into a table format.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/kavindus0/StringToTableConverter.git
   ```

2. Run the script:
   ```
   python string_to_table.py
   ```

3. Enter the string of space-separated data when prompted.

4. The script will generate a table based on the input string and display it.

## Example

Input:
```
id Name age city phone 1 Tolkiens 34 matara 09878987 2 Martin 33 jaffna 67678980 3 Rowling 28 colombo 12345678 4 Dickens 45 kandy 98765432 5 Austen 31 galle 87654321 6 Hemingway 39 trincomalee 23456789 7 Fitzgerald 36 negombo 34567890
```

Output:
```
+----+-----------+-----+-------------+----------+
| Id |   Name    | Age |     City    |  Phone   |
+----+-----------+-----+-------------+----------+
|  1 |  Tolkiens |  34 |   matara    | 9878987  |
|  2 |   Martin  |  33 |   jaffna    | 67678980 |
|  3 |  Rowling  |  28 |   colombo   | 12345678 |
|  4 |  Dickens  |  45 |    kandy    | 98765432 |
|  5 |   Austen  |  31 |    galle    | 87654321 |
|  6 | Hemingway |  39 | trincomalee | 23456789 |
|  7 | Fitzgerald|  36 |   negombo   | 34567890 |
+----+-----------+-----+-------------+----------+
```

## License

This project is licensed under the MIT License
 - see the [LICENSE](LICENSE) file for details.
