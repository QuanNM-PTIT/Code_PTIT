# ĐỀ BÀI: LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG

## KIỂU DỮ LIỆU VÀ PHÉP TOÁN

### CHELLO - HELLO WORLD

Viết chương trình in ra màn hình dòng chữ:

Hello PTIT.

### **Input**

Không có dữ liệu vào

### **Output**

Hello PTIT.

## LẬP TRÌNH JAVA CƠ BẢN

### HELLOFILE - HELLO FILE

Dữ liệu văn bản chứa trong file Hello.txt

Yêu cầu đọc nội dung từ file văn bản Hello.txt và in kết quả ra màn hình.

Input:

Không có dữ liệu vào

Output:

Nội dung trong file văn bản Hello.txt

### HELLOJAR - HỌC PHÍ

Học phí của Học viện được thu theo quy định và thay đổi theo từng thời điểm.

Hãy tính học phí của một sinh viên dựa vào dữ liệu đăng ký học và quy định thu học phí.

Dữ liệu vào cho thông tin về Mã sinh viên, Họ tên, số môn học, mã môn học, tên môn học, số tín chỉ, Số QĐ, Tên QĐ, Đơn giá thu học phí như ví dụ.

Cho file jar bao gồm các class như sau:

![Alt text](./img/HELLOJAR_1.png)

Nhiệm vụ của bạn là tính toán và in ra thông tin tiền học phí phải đóng như định dạng mẫu.

 | Input | Output |
|---|---|
| B20DCCN001  Nguyễn Văn A  2  INT1155  Tin học cơ sở 2  2  INT1332  Lập trình hướng đối tượng  3  QD123  QD123 HP  550000 | Mã sinh viên: B20DCCN001  Họ tên: Nguyễn Văn A  Các môn học:  Tin học cơ sở 2  Lập trình hướng đối tượng  Học phí phải nộp là: 2750000.0  Theo QĐ: QD123 |

### J01001 - HÌNH CHỮ NHẬT

Cho độ dài hai cạnh của hình chữ nhật. Giá trị không quá 104.

Viết chương trình tính chu vi và diện tích của hình chữ nhật đó. Nếu dữ liệu không hợp lệ (chiều dài hoặc chiều rộng ≤ 0 thì in ra số 0)

**Input**

Có duy nhất một dòng ghi hai số nguyên, cách nhau một khoảng trống.

**Output**

In kết quả trên một dòng, chu vi rồi đến diện tích, cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 10 2 | 24 20 |

### J01002 - TÍNH TỔNG N SỐ NGUYÊN DƯƠNG ĐẦU TIÊN

Cho số nguyên dương N.

Hãy tính S = 1 + 2 + ... + N

**Dữ liệu vào:**

- Dòng đầu ghi số bộ test, không quá 10
- Mỗi dòng ghi một số nguyên dương N, không quá 10^9
 
**Kết quả:**

Với mỗi test, ghi kết quả trên một dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  10  20 | 55  210 |

### J01003 - GIẢI PHƯƠNG TRÌNH BẬC NHẤT

Phương trình bậc nhất là phương trình dạng ax + b = 0.  
 Viết chương trình nhập vào hệ số a,b là các số thực và thực hiện giải phương trình bậc nhất.

- Nếu phương trình vô nghiệm thì in ra **VN**
- Nếu phương trình có vô số nghiệm thì in ra **VSN**
- Nếu phương trình có nghiệm duy nhất thì in ra với định dạng luôn 2 chữ số thập phân.
 
**Input**

Chỉ có hai số thực a và b.

**Output**

Ghi ra kết quả theo yêu cầu.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2 -1 | 0.50 |

### J01004 - SỐ NGUYÊN TỐ

Viết chương trình kiểm tra một số nguyên dương có phải **số nguyên tố** hay không. Dòng đầu của dữ liệu vào ghi số bộ test. Mỗi dòng tiếp theo có một nguyên dương không quá 9 chữ số. Kết quả in ra YES nếu đó là số nguyên tố, in ra NO nếu ngược lại.

 | **Input** | **Output** |
|---|---|
| 3  123456  997  111111111 | NO  YES  NO |

### J01005 - CHIA TAM GIÁC

Cho một tam giác cân có độ dài đáy bằng 1 và chiều cao bằng H. Bạn cần chia tam giác này thành N phần có diện tích bằng nhau và song song với đáy.

![Alt text](./img/J01005_1.png)

Hãy in ra N-1 số là khoảng cách từ lát cắt thứ i tới đỉnh của tam giác.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 100).

Mỗi test gồm 2 số nguyên N và H (2 ≤ ≤ N ≤ 1000, 1 ≤ H ≤ 100 000).

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng với 6 chữ số sau dấu phảy.

 | Input: | Output |
|---|---|
| 2  3 2  2 100000 | 1.154701 1.632993  70710.678119 |

### J01006 - TÍNH SỐ FIBONACCI

Dãy số Fibonacci được định nghĩa theo công thức như sau:

F1 = 1

F2 = 1

Fn = Fn-1 + Fn-2 với n&gt;2

Viết chương trình tính số Fibonacci thứ n (với n không quá 92)

**Dữ liệu vào:** Dòng đầu ghi số bộ test. Mỗi bộ test là một số nguyên n.

**Kết quả:** Với mỗi bộ test, ghi ra số Fibonacci thứ n trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  2  5  20 | 1  5  6765 |

### J01007 - KIỂM TRA SỐ FIBONACCI

Cho số nguyên dương n. Hãy kiểm tra xem n có phải là số trong dãy Fibonacci hay không?

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một số nguyên dương n.
- T, n thỏa mãn ràng buộc :1 ≤ T ≤ 100; 0≤n≤1018.
 
**Output:**

- Đưa ra “YES” hoặc “NO” tương ứng với n là số Fibonacci hoặc không phải số Fibonacci của mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  8  15 | YES  NO |

### J01008 - PHÂN TÍCH THỪA SỐ NGUYÊN TỐ

Hãy phân tích một số nguyên dương thành tích các thừa số nguyên tố.

**Dữ liệu vào:** Dòng đầu tiên ghi số bộ test. Mỗi bộ test viết trên một dòng số nguyên dương n không quá 9 chữ số.

**Kết quả:** Mỗi bộ test viết ra thứ tự bộ test, sau đó lần lượt là các số nguyên tố khác nhau có trong tích, với mỗi số viết thêm số lượng số đó. Xem ví dụ để hiểu rõ hơn về cách viết kết quả.

Ví dụ

 | **Input** | **Output** |
|---|---|
| 3  60  128  10000 | Test 1: 2(2) 3(1) 5(1)  Test 2: 2(7)  Test 3: 2(4) 5(4) |

### J01009 - TỔNG GIAI THỪA

| Viết chương trình tính tổng S = 1 + 1.2 + 1.2.3 + ...+1.2.3...n.  **Dữ liệu vào** chỉ có một dòng ghi số n không quá 20.  **Kết quả** cũng được ghi trên một dòng duy nhất. | \| **Input** \| **Output** \| \|---\|---\|---\| \| 3 \| 9 \| |
|---|

### J01010 - CẮT ĐÔI

Với một vài số nguyên dương có 1 chữ số, khi cắt đôi số đó theo chiều ngang và lấy nửa phía trên thì ta vẫn có một số nguyên. Cụ thể:

- Số 0 cắt đôi vẫn ra số 0
- Số 1 cắt đôi vẫn ra số 1
- Số 8 cắt đôi ra số 0
- Số 9 cắt đôi ra số 0
- Các số khác cắt đôi sẽ không hợp lệ.
 
Cho một số nguyên dương không quá 18 chữ số. Hãy in ra kết quả “cắt đôi” của số đó.

Nếu không hợp lệ thì ghi ra INVALID. Chú ý: nếu cắt đôi ra một dãy toàn 0 thì cũng được coi là không hợp lệ. Kết quả cắt đôi thì không tính chữ số 0 ở đầu.

**Input**

Dòng đầu ghi số bộ test. Mỗi bộ test ghi một số nguyên dương không quá 18 chữ số.

**Output**

Ghi ra kết quả tính toán

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  1890  3681  8919 | 1000  INVALID  10 |

### J01011 - BỘI SỐ CHUNG - ƯỚC SỐ CHUNG

Tìm bội số chung nhỏ nhất và ước số chung lớn nhất của hai số nguyên dương a, b.

**Input:

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- T dòng tiếp theo mỗi dòng có một cặp số a, b.
- T, a, b thỏa mãn ràng buộc: 1≤T≤100; 1≤a, b≤108;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5 10  14 8 | 10 5  56 2 |

### J01012 - ƯỚC SỐ CHIA HẾT CHO 2

Cho số nguyên dương N.

Nhiệm vụ của bạn là hãy xác định xem có bao nhiêu ước số của N chia hết cho 2?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 100).

Mỗi bộ test gồm một số nguyên N (1 ≤ N ≤ 109)

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

**Ví dụ:**

 | Input: | Output: |
|---|---|
| 2  9  8 | 0  3 |

### J01013 - TỔNG ƯỚC SỐ - 1

Cho N số nguyên. Nhiệm vụ của bạn là phân tích các số nguyên đã cho dưới dạng tích của các thừa số nguyên tố, sau đó tính tổng các ước số nguyên tố này.

**Input:**

- Dòng đầu tiên số nguyên N (1 ≤ N ≤ 106).
- N dòng tiếp theo, mỗi dòng gồm một số nguyên có giá trị không vượt quá 2\*106.
 
**Output:**

In ra một số nguyên là đáp án tìm được.

**Ví dụ:**

 | Input: | Output: |
|---|---|
| 5  7  9  10  13  100 | 47 |

Giải thích test:

7 = 7

9 = 3 x 3 à 3 + 3 = 6

10 = 2 x 5 à 2 + 5 = 7

13 = 13

100 = 2 x 2 x 5 x 5 à 2+2+5+5 = 14

Cộng lại, 7 + 6 + 7 + 13 + 14 = 47.

### J01014 - ƯỚC SỐ NGUYÊN TỐ LỚN NHẤT

Cho số nguyên dương N. Hãy đưa ra ước số nguyên tố lớn nhất của N.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test ghi số nguyên dương N.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 2≤N≤1010.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 2  315  31 | 7  31 |

### J01016 - CHỮ SỐ 4 VÀ CHỮ SỐ 7

Cho số nguyên dương N có không quá 18 chữ số. Hãy đếm xem số chữ số 4 cộng với số chữ số 7 trong N có phải bằng 4 hay bằng 7 hay không.

**Input**

Chỉ có số N

**Output**

Ghi ra YES hoặc NO tùy thuộc kết quả kiểm tra

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 40047 | NO |
| 7747774 | YES |
| 1000000000000000000 | NO |

### J01017 - SỐ LIỀN KỀ

Viết chương trình kiểm tra số nguyên dương N có thỏa mãn tính chất: tất cả các chữ số cạnh nhau chỉ sai khác nhau đúng một đơn vị hay không. Ví dụ: số 123212 là số thỏa mãn, số 34578 không thỏa mãn.

**Input**

Dòng đầu ghi số số test (không quá 20). Mỗi test là 1 số nguyên dương N có ít nhất 2 chữ số, nhưng không quá 18 chữ số.

**Output**

Ghi ra YES hoặc NO

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  123212  5654345676  10233211123 | YES  YES  NO |

### J01018 - SỐ KHÔNG LIỀN KỀ

Cho số nguyên dương N. Hãy kiểm tra xem N có thỏa mãn đồng thời hai tính chất sau đây hay không?

- Tổng chữ số của N chia hết cho 10
- Các chữ số cạnh nhau đều khác nhau đúng 2 đơn vị
 
**Input**

Dòng đầu ghi số bộ test. Mỗi bộ test ghi trên một dòng số nguyên dương N. N có ít nhất 3 chữ số nhưng không quá 18 chữ số.

**Output**

Ghi ra YES hoặc NO tùy thuộc kết quả kiểm tra

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  1353  246864  123435 | NO  YES  NO |

### J01021 - TÍNH LŨY THỪA

Cho hai số nguyên không âm a và b. Hãy tính ab.

Nếu kết quả quá lớn hãy chia dư cho 109 + 7.

**Input**

Gồm không quá 20 bộ test, mỗi test ghi trên một dòng hai số a,b; a không quá 9 chữ số, b không quá 18 chữ số.

Input kết thúc khi a = b = 0

**Output**

Với mỗi test ghi ra kết quả tính được trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2 3  2 4  3 2  0 0 | 8  16  9 |

### J01022 - XÂU NHỊ PHÂN

Người ta tạo ra một dãy xâu ký tự nhị phân X\[\] trong đó:

X\[1\] = “0”

X\[2\] = “1”

X\[n\] = X\[n-2\] + X\[n-1\] với n&gt;2

Với phép cộng (+) là phép nối hai xâu với nhau.

Cho hai số tự nhiên N và K (1&lt;N&lt;93; K đảm bảo trong phạm vi của xâu X\[N\]).

Hãy xác định ký tự thứ K trong xâu X\[N\] là ký tự ‘0’ hay ký tự ‘1’.

**Input:** Dòng 1 ghi số bộ test. Mỗi bộ test ghi trên một dòng 2 số nguyên N và K.

**Output:** Ghi ra màn hình kết quả tương ứng với từng bộ test.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  6 4  8 19 | 0  1 |

### J01023 - TOÁN LỚP BA

Cho một biểu thức trong phạm vi hai chữ số với các phép toán cộng trừ nhân chia. *Các toán hạng và kết quả đảm bảo là số nguyên dương có hai chữ số*, *nếu có phép chia thì phải thỏa mãn tính chia hết.*

Người ta có thể ẩn đi một số chữ số hoặc phép toán bằng cách điền dấu chấm hỏi (?). Nhiệm vụ của bạn là khôi phục các dấu chấm hỏi và in ra phép toán chính xác ban đầu. Nếu không thể có kết quả đúng thì ghi ra WRONG PROBLEM!

**Dữ liệu vào**

Dòng đầu ghi số bộ test T (1 ≤ T ≤ 100).

T dòng tiếp theo, mỗi dòng là một biểu thức *có thể* có các dấu ?.

*Dữ liệu vào đảm bảo chỉ có duy nhất một kết quả đúng hoặc không thể có kết quả đúng.*

**Kết quả**

Với mỗi bộ test, ghi ra biểu thức đúng tìm được. Hoặc WRONG PROBLEM!

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2    ?0 ? 12 = 28    40 / ?3 = ?? | 40 - 12 = 28  WRONG PROBLEM! |

### J01024 - SỐ TAM PHÂN

Một số được gọi là “tam phân” nếu chỉ có các chữ số 0,1,2. Nhập vào một số nguyên dương không quá 9 chữ số, hãy kiểm tra xem đó có phải số tam phân hay không. Dòng đầu là số bộ test, mỗi dòng tiếp theo ghi một số cần kiểm tra. Nếu đúng in ra YES, nếu sai in ra NO.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  1214  10210221  22222222 | NO  YES  YES |

### J01025 - HÌNH VUÔNG

Cho 2 hình chữ nhật trên mặt phẳng Oxy. Cần tìm hình vuông có kích thước nhỏ nhất sao cho phủ kín được 2 hình chữ nhật đã cho.

**Input:**

2 dòng, mỗi dòng gồm 4 số nguyên lần lượt mô tả điểm trái dưới và phải trên của hình chữ nhật. Các tọa độ có giá trị tuyệt đối không vượt quá 1000.

**Output:**

In ra diện tích của hình vuông tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 6 6 8 8  1 8 4 9 | 49 |

### J01026 - SỐ CHÍNH PHƯƠNG

Nhập một số nguyên dương không quá 9 chữ số. Hãy kiểm tra xem đó có phải số chính phương hay không.

Dòng đầu của dữ liệu vào ghi số bộ test, mỗi bộ test là một số nguyên dương ghi trên một dòng.

**Kết quả:** ghi ra YES nếu đúng và NO nếu không.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  11  121  361 | NO  YES  YES |

### J03033 - BỘI SỐ CHUNG NHỎ NHẤT

Viết chương trình tính bội số chung nhỏ nhất của hai số nguyên dương lớn (có thể đến 500 chữ số)

**Input:**  
 Dòng 1 ghi số bộ test. Mỗi bộ test gồm 2 dòng, mỗi dòng ghi một số.

**Output:**  
 Với mỗi bộ test ghi ra kết quả trên một dòng.

  
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3    12    100    1212    8888    121212121212121212    45678978 | 300    26664    102534181818181818079284 |

### J03035 - ĐIỀN CHỮ SỐ

Cho hai số nguyên dương A, B có cùng số chữ số, trong đó số A đã bị ẩn đi một số vị trí với dấu ?.

Hãy đếm xem từ số A như vậy có thể tạo được bao nhiêu số lớn hơn B bằng cách điền chữ số bất kỳ vào vị trí ?. Các chữ số điền vào các vị trí ? khác nhau có thể khác nhau.

**Input**

Dòng đầu ghi số bộ test.

Mỗi test viết trên hai dòng số A và số B, không quá 10 chữ số. Trong đó số A có một số vị trí được ẩn đi với dấu ?.

**Output**

Với mỗi test, ghi ra số lượng các số tạo được từ A cho giá trị lớn hơn B.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  36?1?8  236428  8?3  910  ?  5 | 100  0  4 |

## XÂU KÝ TỰ

### J01020 - ĐẦY ĐỦ CÁC CHỮ SỐ

Cho số nguyên dương N không quá 106. Bắt đầu từ số N, bạn thực hiện nhân đôi (N\*2), nhân ba (N\*3) và tiếp tục như vậy cho đến khi tất cả các chữ số thập phân từ 0 đến 9 đều đã xuất hiện đâu đó trong các giá trị kết quả.

Hãy tìm số K nhỏ nhất sao cho khi gặp giá trị K thì tất cả các chữ số từ 0 đến 9 đều đã xuất hiện. Nếu không thể tìm được số K thì in ra **Impossible**

**Dữ liệu vào:**

- Dòng đầu ghi số bộ test T (không quá 100)
- Mỗi test ghi duy nhất số nguyên N (1 ≤ N ≤ 106)
 
**Kết quả:** Ghi ra trên một dòng số K tìm được. Hoặc **Impossible**

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5  0  1  2  11  1692 | Impossible  10  90  110  5076 |

### J02037 - DÃY ƯU THẾ

Cho dãy A\[\] chỉ bao gồm các số nguyên dương không quá 105 nhưng không biết trước số phần tử của dãy. Người ta gọi dãy A\[\] là dãy ưu thế nếu thỏa mãn 1 trong 2 điều kiện sau đây:

- Dãy gọi là ưu thế chẵn nếu số phần tử của dãy là chẵn và số lượng số chẵn trong dãy nhiều hơn số lượng số lẻ.
- Dãy gọi là ưu thế lẻ nếu số phần tử của dãy là lẻ và số lượng số lẻ trong dãy nhiều hơn số lượng số chẵn.
 
Hãy kiểm tra xem dãy A\[\] có phải là dãy ưu thế hay không.

**Input:**

- Dòng đầu ghi số bộ test, không quá 10
- Mỗi bộ test là một dãy các số nguyên dương (không quá 104) và có không quá 200 số, các số cách nhau 1 khoảng trống, không biết trước số lượng phần tử.
 
**Output:**

- Nếu dãy A\[\] thỏa mãn là dãy ưu thế thì in ra YES, nếu không in ra NO
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  11 22 33 44 55 66 77  23 34 45 56 67 78 89 90 121 131 141 151 161 171 | YES  NO |

### J03004 - CHUẨN HÓA XÂU HỌ TÊN - 1

Một xâu họ tên được coi là viết chuẩn nếu chữ cái đầu tiên mỗi từ được viết hoa, các chữ  
 cái khác viết thường. Các từ cách nhau đúng một dấu cách và không có khoảng trống  
 thừa ở đầu và cuối xâu. Hãy viết chương trình đưa các xâu họ tên về dạng chuẩn.  
 **Dữ liệu vào:** Dòng 1 ghi số bộ test. Mỗi bộ test ghi trên một dòng xâu ký tự họ tên, không quá  
 80 ký tự.  
 **Kết quả:** Với mỗi bộ test ghi ra xâu ký tự họ tên đã chuẩn hóa.  
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3    nGuYEN vAN naM    tRan TRUNG hiEU    vO le hOA bINh | Nguyen Van Nam    Tran Trung Hieu    Vo Le Hoa Binh |

### J03005 - CHUẨN HÓA XÂU HỌ TÊN - 2

Theo quy tắc viết tên tiếng Anh, họ tên sẽ thường được viết lại theo dạng chuẩn trong đó phần họ được viết sau cùng, phân tách với phần tên đệm và tên bởi dấu phẩy. Các chữ cái của phần họ đều viết hoa.

Cho trước các xâu họ tên (có thể không chuẩn). Hãy đưa về dạng chuẩn tương ứng.

**Dữ liệu vào:**

- Dòng 1 ghi số N là xâu họ tên trong danh sách
- N dòng tiếp theo ghi lần lượt các xâu họ tên (không quá 50 ký tự)
 
**Kết quả:** Ghi ra các xâu chuẩn.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 4   nGUYEn quaNG vInH   tRan thi THU huOnG   nGO quoC VINH   lE tuAn aNH | Quang Vinh, NGUYEN  Thi Thu Huong, TRAN  Quoc Vinh, NGO  Tuan Anh, LE |

### J03006 - SỐ ĐẸP 1

Một số được coi là đẹp nếu đó là số thuận nghịch và chỉ toàn các chữ số chẵn. Viết chương trình đọc vào các số nguyên dương có không quá 500 chữ số và kiếm tra xem số đó có đẹp hay không.

**Dữ liệu vào:**

Dòng đầu tiên ghi số bộ test.

Mỗi bộ test viết trên một dòng số nguyên dương n không quá 500 chữ số.

**Kết quả:**

 Mỗi bộ test viết ra trên một dòng chữ YES nếu đó là số đẹp, chữ NO nếu ngược lại

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  123456787654321  86442824468  8006000444422220000222244440006008  235365789787654324567856578654356786556 | NO  YES  YES  NO |

### J03007 - SỐ ĐẸP 2

Một số được coi là đẹp nếu đó là số thuận nghịch, bắt đầu và kết thúc bằng chữ số 8 và tổng chữ số chia hết cho 10. Viết chương trình đọc vào các số nguyên dương có không quá 500 chữ số và kiếm tra xem số đó có đẹp hay không.

**Dữ liệu vào:**

Dòng đầu tiên ghi số bộ test.

Mỗi bộ test viết trên một dòng số nguyên dương n không quá 500 chữ số.

**Kết quả:**

 Mỗi bộ test viết ra trên một dòng chữ YES nếu đó là số đẹp, chữ NO nếu ngược lại

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  123456787654321  8644281154664511824468  8006000444400000000000044440006008  82123400000000000000000000000432128 | NO  NO  YES  YES |

### J03008 - SỐ ĐẸP 3

Một số được coi là đẹp nếu đó là số thuận nghịch và chỉ toàn các chữ số nguyên tố. Viết chương trình đọc vào các số nguyên dương có không quá 500 chữ số và kiếm tra xem số đó có đẹp hay không.

**Dữ liệu vào:**

Dòng đầu tiên ghi số bộ test.

Mỗi bộ test viết trên một dòng số nguyên dương n không quá 500 chữ số.

**Kết quả:**

 Mỗi bộ test viết ra trên một dòng chữ YES nếu đó là số đẹp, chữ NO nếu ngược lại

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  123456787654321  235755557532  2222333355557777235775327777555533332222 | NO  YES  YES |

### J03009 - TẬP TỪ RIÊNG CỦA HAI XÂU

Cho hai xâu ký tự S1 và S2. Hãy viết chương trình tìm các từ chỉ xuất hiện trong S1 mà không xuất hiện trong S2. Chú ý: mỗi từ chỉ liệt kê 1 lần.

**Dữ liệu vào:** Dòng 1 ghi số bộ test. Mỗi bộ test gồm 2 dòng, mỗi dòng ghi một xâu ký tự độ dài không quá 200, chỉ bao gồm các ký tự viết thường và các khoảng trống.

**Kết quả:** Với mỗi bộ test ghi ra các từ có trong S1 mà không có trong S2. Các từ được ghi theo thứ tự từ điển.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  abc ab ab ab abcd  ab abc  aaa xyz ab zzz abc dd dd abc  xyz dd ttt sas cdc | abcd  aaa ab abc zzz |

### J03010 - ĐỊA CHỈ EMAIL

Địa chỉ email của các cán bộ, giảng viên PTIT được tạo ra bằng cách viết đầy đủ tên và ghép với các chữ cái đầu của họ và tên đệm. Nếu có nhiều người cùng email thì từ người thứ 2 sẽ thêm số thứ tự vào email đó.

Cho trước các xâu họ tên (có thể không chuẩn). Hãy tạo ra các địa email tương ứng.

**Dữ liệu vào:**

- Dòng 1 ghi số N là xâu họ tên trong danh sách
- N dòng tiếp theo ghi lần lượt các xâu họ tên (không quá 50 ký tự)
 
**Kết quả:** Ghi ra các email được tạo ra.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 4   nGUYEn quaNG vInH   tRan thi THU huOnG   nGO quoC VINH   lE tuAn aNH | vinhnq@ptit.edu.vn  huongttt@ptit.edu.vn  vinhnq2@ptit.edu.vn  anhlt@ptit.edu.vn |

### J03011 - ƯỚC SỐ CHUNG LỚN NHẤT CỦA SỐ NGUYÊN LỚN

Cho hai số a và b trong đó a≤1012, b≤10250. Nhiệm vụ của bạn là tìm ước số chung lớn nhất của hai số a, b.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- T dòng tiếp đưa các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào số a; dòng tiếp theo đưa vào số b.
- Các số T, a, b thỏa mãn ràng buộc: 1≤T≤100; 1≤a≤1012; 1≤b≤10250;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  1221  1234567891011121314151617181920212223242526272829 | 3 |

### J03012 - TỔNG SỐ NGUYÊN LỚN - 1

Cho hai số rất lớn X và Y được biểu diễn như hai xâu ký tự. Nhiệm vụ của bạn là tìm X+Y?

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi test gồm hai dòng: dòng thứ nhất đưa xâu X; dòng tiếp theo đưa vào xâu Y.
- T, X, Y thỏa mãn ràng buộc : 1≤T≤100; 0≤length(X), length(Y)≤103.
 
**Output:**

- Đưa ra số kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 1    12  198111 | 198123 |

### J03013 - HIỆU SỐ NGUYÊN LỚN - 1

Cho hai số rất lớn X và Y được biểu diễn như hai xâu ký tự. Nhiệm vụ của bạn là tìm |X-Y|?

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi test gồm hai dòng: dòng thứ nhất đưa xâu X; dòng tiếp theo đưa vào xâu Y.
- T, X, Y thỏa mãn ràng buộc : 1≤T≤100; 0≤length(X), length(Y)≤103.
 
**Output:**

- Đưa ra số kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | Input: | Output: |
|---|---|
| 2    978  12977  100  1000000 | 11999  0999900 |

### J03014 - TỔNG SỐ NGUYÊN LỚN - 2

Cho hai xâu ký tự A và B mô tả hai số nguyên dương lớn có thể có đến 1000 chữ số.

Có thể có các chữ số 0 ở đầu của A và B.  
 Hãy tính tổng A + B.

Kết quả ghi ra cần loại bỏ các chữ số 0 ở đầu nếu có.

**Input**

Có hai dòng ghi 2 số A và B.

**Output**

Ghi ra kết quả A + B.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 121212121212121212  45678978 | 121212121257800190 |

### J03015 - HIỆU SỐ NGUYÊN LỚN  - 2

Cho hai xâu ký tự A và B mô tả hai số nguyên dương lớn có thể có đến 1000 chữ số.

Có thể có các chữ số 0 ở đầu của A và B.  
 Hãy tính A - B.

Kết quả có thể âm, khi ghi ra cần loại bỏ các chữ số 0 ở đầu nếu có.

Tất nhiên nếu kết quả là -0 thì ghi ra là 0.

**Input**

Có hai dòng ghi 2 số A và B.

**Output**

Ghi ra kết quả A - B.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 000123456789012345678901234567890  00000000000000001234567890 | 123456789012345678900000000000 |

### J03016 - CHIA HẾT CHO 11

Cho số tự nhiên N, hãy kiểm tra xem N có phải là số chia hết cho 11 hay không? Đưa ra 1 nếu N chia hết cho 11, trái lại đưa ra 0.

**Input:**

- **Dòng** đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test là một số tự nhiên N.
- T, N thỏa mãn ràng buộc: 1≤ T ≤100; 0≤ N ≤101000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 2    76945    363588395960667043875487 | 1    0 |

### J03017 - LOẠI BỎ “100”

Cho xâu ký tự S chỉ bao gồm các ký tự ‘0’ và ‘1’. Nhiệm vụ của bạn là loại bỏ các xâu con “100” trong S và đưa ra độ dài lớn nhất xâu con bị loại bỏ. Ví dụ S =” 1011110000” ta nhận được kết quả là 6 vì ta cần loại bỏ xâu “110000” có độ dài 6.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test là một xâu ký tự nhị phân S được viết trên một dòng.
- T, S thỏa mãn ràng buộc: 1≤ T ≤100; 1≤ Length(S)≤105.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | Input: | Output: |
|---|---|
| 2    010010    1011110000 | 3    6 |

### J03018 - TÌM SỐ DƯ

Hãy tính giá trị biểu thức

![Alt text](./img/J03018_1.png)

**Input:**

- Dòng đầu là số lượng bộ test T (T ≤ 100).
- Mỗi test gồm một xâu biểu diễn số nguyên n, n có không quá 100 000 kí tự.
 
**Output:**

- Với mỗi test in ra đáp án tìm được trên một dòng.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  4  123456789 | 4  0 |

### J03019 - XÂU CON LỚN NHẤT

**Xâu con** của một xâu ký tự S được tạo ra bằng cách lấy một hoặc nhiều ký tự trong S và giữ nguyên thứ tự ban đầu.

Cho xâu S chỉ bao gồm các chữ cái viết thường. Hãy in ra xâu con có thứ tự từ điển là lớn nhất.

**Input**

Chỉ có xâu ký tự S, độ dài không quá 100000. Không có khoảng trống.

**Output**

Ghi ra xâu con có thứ tự từ điển lớn nhất.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| ababba | bbba |
| abbcbccacbbcbaaba | cccccbba |

### J03020 - TÌM TỪ THUẬN NGHỊCH DÀI NHẤT

Cho dữ liệu vào dạng văn bản. Hãy tìm ra từ thỏa mãn tính chất ***thuận nghịch có độ dài  
 lớn nhất*** và cho biết từ đó ***xuất hiện bao nhiêu lần***. Nếu có nhiều từ cùng  
 có độ dài lớn nhất thì in ra tất cả các từ đó theo thứ tự xuất hiện .  
 **Dữ liệu vào:** Không quá 1000 từ.  
 **Kết quả**:

Ghi ra trên một dòng từ thuận nghịch có độ dài lớn nhất và số lần xuất hiện của  
 nó. Nếu có nhiều từ cùng có độ dài lớn nhất thì các từ được liệt kê theo thứ tự xuất  
 hiện ban đầu.  
 **Ví dụ:**

 | **Dữ liệu vào** | **KẾT QUA** |
|---|---|
| AAA BAABA HDHDH ACBSD SRGTDH DDDDS    DUAHD AAA AD DA HDHDH AAA AAA AAA AAA    DDDAS HDHDH HDH AAA AAA AAA AAA AAA    AAA AAA AAA    DHKFKH DHDHDD HDHDHD DDDHHH HHHDDD    TDTD | HDHDH 3 |

### J03021 - ĐIỆN THOẠI CỤC GẠCH

Một thời không quá xa, điện thoại di động với chỉ các tính năng nghe, gọi, nhắn tin vẫn còn chiếm đại đa số thiết bị cầm tay tại Việt Nam. Khi nhắn tin, người nhắn sẽ bấm các phím số một đến bốn lần liên tiếp tương ứng với ký tự đi kèm ghi trên đó.

Cụ thể: các số và chữ cái tương ứng gồm:

2: ABC, 3: DEF, 4: GHI, 5: JKL

6: MNO, 7: PQRS, 8: TUV, 9: WXYZ

Cho trước dãy ký tự mô tả tin nhắn (không tính các ký tự khác ngoài danh sách nêu trên). Hãy kiểm tra xem dãy số được nhấn ứng với dãy ký tự đó có phải số thuận nghịch hay không (chỉ xét tương ứng giữa số và ký tự, không tính số đó được nhấn bao nhiêu lần, ví dụ tất cả A,B,C,a,b,c đều chỉ là một chữ số 2).

**Input**

Dòng đầu tiên là số bộ test, không quá 1000.

Mỗi test là dãy ký tự mô tả tin nhắn.

**Output**

Ghi ra kết quả kiểm tra, YES nếu dãy số là thuận nghịch, NO nếu ngược lại.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  BOHIMA  IamACoder | YES  NO |

### J03022 - XỬ LÝ VĂN BẢN

Cho dữ liệu vào là luồng văn bản bất kỳ, gồm các ký tự viết hoa, viết thường, các ký tự số và các dấu câu, không có các ký tự đặc biệt khác. Người ta muốn tách văn bản thành các câu. Mỗi câu in trên một dòng.

Một câu được định nghĩa là dãy ký tự có *ít nhất 1 ký tự chữ cái hoặc chữ số*, không chứa các dấu ngắt câu gồm: dấu chấm (.), dấu chấm hỏi (?) và dấu chấm cảm (!).

Dấu phẩy (,) và dấu hai chấm (:) không được coi là dấu ngắt câu.

Nhiệm vụ của bạn là in ra mỗi câu trên một dòng, ký tự đầu câu viết hoa, các ký tự khác viết thường, các từ cách nhau đúng một khoảng trống. Không có khoảng trống ở đầu và cuối câu, và không in ra các dấu ngắt câu.

**Input**

Gồm một luồng văn bản không quá 100 dòng, mỗi dòng không quá 200 ký tự.

**Output**

In ra các câu, mỗi câu trên một dòng theo quy tắc đã cho.

**Ví dụ**

 | **Input** |
|---|
| ky thi LAP TRINH ICPC PTIT bat dau to chuc tu nam 2010. nhu vay, nam nay la tron 10 nam!   vay CO PHAI NAM NAY LA KY THI LAN THU 10? khong phai! nam nay la KY THI LAN THU 11. |
| **Output** |
| Ky thi lap trinh icpc ptit bat dau to chuc tu nam 2010  Nhu vay, nam nay la tron 10 nam  Vay co phai nam nay la ky thi lan thu 10  Khong phai  Nam nay la ky thi lan thu 11 |

### J03023 - SỐ LA MÃ

Bảng chữ số La Mã bao gồm các chữ cái với ý nghĩa I=1; V=5; X=10; L=50; C=100;D=500; M=1000. Một số quy tắc viết các số La Mã như sau:

- Tính từ trái sang phải giá trị của các chữ số và nhóm chữ số giảm dần.
- I chỉ có thể đứng trước V hoặc X, X chỉ có thể đứng trước L hoặc C, C chỉ có thể đứng trước D hoặc M.
- Các chữ cái I, X, C, M, không được lặp lại quá ba lần liên tiếp; các chữ cái V, L, D không được lặp lại quá một lần liên tiếp.
 
Bài toán đặt ra là cho một xâu ký tự mô tả **đúng** một số La Mã. Hãy tính giá trị thập phân của số đó

**Input:** Dòng đầu ghi số bộ test. Mỗi bộ test ghi trên một dòng dãy ký tự số La Mã.

**Output:** Với mỗi bộ test ghi ra kết quả tương ứng

**Ví dụ:**

 | **Input** | **Ouput** |
|---|---|
| 3  XIX  DC  CD | 19  600  400 |

### J03024 - SỐ ƯU THẾ

Cho một số nguyên dương lớn có nhiều hơn 20 chữ số nhưng không quá 1000 chữ số. Một số nguyên dương được coi là “số ưu thế chẵn” nếu số chữ số của nó là chẵn và số chữ số chẵn nhiều hơn số chữ số lẻ.

Một số nguyên dương được coi là “số ưu thế lẻ” nếu số chữ số của nó là lẻ và số chữ số lẻ nhiều hơn số chữ số chẵn.

Hãy kiểm tra xem số đó có phải là số ưu thế (chẵn hoặc lẻ) hay không. Chú ý: trường hợp số lượng chữ số chẵn và số lượng chữ số lẻ bằng nhau thì không được coi là số ưu thế.

**Dữ liệu vào**

- Dòng đầu ghi số bộ test, không quá 10
- Mỗi bộ test là một dãy ký tự có độ dài không quá 1000, không có khoảng trống
 
**Kết quả**

- Nếu dữ liệu vào không phải là một số nguyên hợp lệ (có ký tự không phải số hoặc bắt đầu bằng chữ số 0) thì in ra INVALID
- Nếu dữ liệu vào thỏa mãn là số ưu thế thì in ra YES, nếu không in ra NO
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  01234aa32432432432534545b987978  1234567890123456789000  999999999999999999999999999999 | INVALID  YES  NO |

### J03025 - XÂU ĐỐI XỨNG

Cho trước một xâu S. Bạn thay đổi đúng 1 kí tự. Hãy kiểm tra xem liệu bạn có thể tạo ra được xâu đối xứng hay không.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 20).

Mỗi test gồm 1 xâu S có độ dài không quá 15 kí tự.

**Output:**

Với mỗi test, in ra “YES” nếu có thể biến đổi xâu S thành xâu đối xứng, in ra “NO” trong trường hợp ngược lại.

**Ví dụ:**

 | Input: | Output |
|---|---|
| 3  abccaa  abbcca  abcda | YES  NO  YES |

### J03026 - XÂU KHÁC NHAU DÀI NHẤT

Cho 2 xâu A và B. Bạn hãy tìm xâu C dài nhất sao cho C chỉ là xâu con của A hoặc B, chứ không phải là xâu con của cả A và B.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 20).

Mỗi test gồm 2 dòng, mô tả xâu A và B, mỗi xâu có độ dài không có 500 kí tự và chỉ gồm các chữ cái thường.

**Output:**

Với mỗi test, in ra độ dài của xâu con khác nhau dài nhất tìm được.

Nếu không có đáp án, in ra -1.

**Ví dụ:**

 | Input: | Output |
|---|---|
| 2  abcd  defgh  a  a | 5  -1 |

Giải thích test 1: Xâu khác nhau dài nhất chính là xâu thứ 2, “defgh”.

### J03027 - RÚT GỌN XÂU KÝ TỰ

Cho một xâu S. Mỗi bước, bạn được phép xóa đi 2 kí tự liền nhau mà giống nhau. Chẳng hạn xâu “aabcc” có thể trở thành “bcc” hoặc “aab” sau 1 lần xóa.

Hỏi xâu cuối cùng thu được là gì? Nếu xâu rỗng, in ra “Empty String”.

**Input:**

Một xâu S chỉ gồm các chữ cái thường, có độ dài không vượt quá 100.

**Output:**

In ra đáp án tìm được.

**Ví dụ:**

 | Test 1 | Test 2 |
|---|---|
| Input:  aaabccddd  Output:  abd | Input:  abba  Output:  Empty String |

### J03028 - MÃ HÓA DRM

Cho một xâu ký tự. Quá trình mã hóa DRM sẽ trải qua ba bước Chia (Divide), Xoay (Rotate) và Trộn (Merge). Ví dụ với xâu: EWPGAJRB quá trình này sẽ diễn ra như sau:

- **Devide:** Xâu ban đầu được chia thành 2 nửa: “EWPG” và “AJRB”.
- **Rotate:** Với mỗi nửa, tính toán giá trị xoay của nó bằng cách tính tổng giá trị các ký tự. (A = 0; B = 1; … Z = 25). Giá trị xoay của “EWPG” là 4 + 22 + 15 + 6 = 47. Tiến hành xoay xâu “EWPG” đi 47 ký tự (tính cả bước chuyển từ Z về A nếu cần) ta sẽ được xâu: “ZRKB”. Tương tự, “AJRB” được chuyển thành “BKSC”
- **Merge:** Trong bước này, mỗi ký tự trong xâu thứ nhất sẽ được xoay theo giá trị của ký tự ở vị trí tương ứng trong xâu thứ 2. Trong ví dụ trên, chữ Z trong xâu thứ nhất sẽ xoay theo giá trị B, tức là 1 vị trí. Do đó sẽ chuyển thành chữ A. Tiếp tục thực hiện với các ký tự tiếp theo ta sẽ có kết quả là “ABCD”.
 
Cho một xâu ký tự chỉ bao gồm các chữ cái in hoa với số lượng ký tự là chẵn, bạn hãy tìm xâu mã hóa DRM tương ứng.

**Input**

Dòng đầu ghi số bộ test T (T≤30).

Mỗi bộ test ghi trên một dòng xâu ký tự cần mã hóa, chỉ gồm các chữ cái in hoa, độ dài là chẵn và không quá 15000 ký tự.

**Output**

Với mỗi test in ra trên một dòng kết quả mã hóa DRM tương ứng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  EWPGAJRB  BB  TPQJDRJWSQXGRRIPXFMINTELHBJA | ABCD  E  FIRSTDATAFILEV |

### J03029 - CHUẨN HÓA CÂU

Một câu trong văn bản được hiểu là dãy ký tự (có cả khoảng trống) cho đến khi gặp dấu ngắt câu hoặc xuống dòng (tức là đôi khi người ta quên viết dấu ngắt câu nhưng cứ xuống dòng là sang một câu mới). Các dấu ngắt câu trong bài toán này bao gồm: dấu chấm (.), dấu chấm cảm (!), dấu chấm hỏi (?).

Hãy viết chương trình chuẩn hóa các câu trong dữ liệu vào với các yêu cầu sau:

- Ký tự đầu mỗi câu viết hoa, các ký tự khác viết thường.
- Các từ cách nhau đúng một khoảng trống.
- Tự động điền thêm dấu chấm (.) nếu xuống dòng mà chưa có dấu ngắt câu.
- Dấu ngắt câu phải viết sát ký tự cuối cùng của câu (không tính khoảng trống)
 
**Input**

Một văn bản không quá 100 dòng.

**Output**

Ghi ra các câu đã chuẩn hóa, mỗi câu 1 dòng.

**Ví dụ**

 | **Input** |
|---|
| Chuong trinh Dao Tao CLC nganh CNTT duoc Thiet Ke theo chuan quoc te.  co 03 chuyen nganh la: Cong nghe phan mem, Tri tue nhan tao va An toan thong tin  muc tieu cua chuong trinh la trang bi cho sinh vien cac ky nang nghe nghiep  moi CAC BAN danG ky thaM giA ! |
| **Output** |
| Chuong trinh dao tao clc nganh cntt duoc thiet ke theo chuan quoc te.  Co 03 chuyen nganh la: cong nghe phan mem, tri tue nhan tao va an toan thong tin.  Muc tieu cua chuong trinh la trang bi cho sinh vien cac ky nang nghe nghiep.  Moi cac ban dang ky tham gia! |

### J03030 - BIẾN ĐỔI A – B

Cho xâu ký tự s chỉ bao gồm hai chữ cái là ‘A’ và ‘B’.

Mỗi bước được phép biến đổi một vị trí bất kỳ trong xâu (A thành B, B thành A) hoặc cũng có thể biến đổi một dãy liên tiếp các ký tự nào đó tính từ đầu xâu.

Hãy tính xem cần ít nhất bao nhiêu bước để biến đổi xâu về dạng toàn chữ cái A.

**Input**

Chỉ có 1 dòng ghi xâu ký tự s, độ dài không quá 1 triệu ký tự.

**Output**

Ghi ra kết quả bài toán

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| AAABBBAAABBB | 4 |

### J03031 - XÂU ĐẦY ĐỦ

Một xâu ký tự được gọi là đầy đủ nếu nó chứa đầy đủ các ký tự từ ‘a’, ..’z’.

Cho xâu ký tự S và số K. Mỗi bước được phép thay thế ký tự này bằng một ký tự khác. Hãy xác định xem có thể thực hiện nhiều nhất K bước để S trở thành đầy đủ hay không?

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào xâu ký tự S; dòng tiếp theo đưa vào số K.
- T, S, K thỏa mãn ràng buộc: 1≤ T ≤100; 0≤ K ≤62; 1≤ length(S) ≤106.
 
**Output:**

- Với mỗi test, ghi ra YES hoặc NO tùy thuộc kết quả kiểm tra.
 
**Ví dụ:**

 | **Input** | **Output:** |
|---|---|
| 2    qwqqwqeqqwdsdadsdasadsfsdsdsdasasas    4    qwqqwqeqqwdsdadsdasadsfsdsdsdasasas    24 | NO  YES |

### J03032 - ĐẢO TỪ

Cho một xâu ký tự str bao gồm nhiều từ trong xâu. Hãy đảo ngược từng từ trong xâu?

**Input**: Dòng đầu tiên đưa vào số lượng bộ test T. Những dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một dòng ghi lại nhiều từ trong xâu str.

**Output**: Đưa ra kết quả mỗi test theo từng dòng.

**Ràng buộc**: T, str thỏa mãn ràng buộc: 1≤T≤100; 2≤length(str)≤106.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  ABC DEF  123 456 | CBA FED  321 654 |

### J03036 - XOAY VÒNG KÝ TỰ

Cho N xâu S\[1\], S\[2\], …, S\[N\] có độ dài bằng nhau. Mỗi bước, với xâu T, bạn được phép xoay vòng 1 kí tự, tức lấy kí tự đầu tiên của T rồi chuyển xuống cuối. Ví dụ xâu “cool” sẽ chuyển thành “oolc”.

Bạn cần phải xoay N xâu sao cho tất cả chúng đều giống nhau. Hãy xác định số bước ít nhất để hoàn thành được công việc này?

**Input:**

Mỗi test bắt đầu bởi số nguyên N (1 ≤ N ≤ 50).

N dòng tiếp theo, mỗi dòng gồm xâu S\[i\] có độ dài không quá 50.

**Output:**

Với mỗi test, in ra số bước ít nhất tìm được, nếu không thể biến đổi, hãy in ra -1.

**Ví dụ:**

 | **Test 1** | **Test 2** | **Test 3** | **Test 4** |
|---|---|---|---|
| Input:  4  xzzwo  zwoxz  zzwox  xzzwo  Output:  5 | Input:  2  molzv  lzvmo  Output:  2 | Input:  3  kc  kc  kc  Output:  0 | Input:  3  aa  aa  ab  Output:  -1 |

Giải thích test 1: Xoay tất cả các xâu thành “zwoxz”.

### J03037 - VÒNG TRÒN

Nam viết bảng chữ cái 2 lần lên trên một vòng tròn, mỗi kí tự xuất hiện đúng 2 lần. Sau đó nối lần lượt các kí tự giống nhau lại. Tổng cộng có 26 đoạn thẳng.

Hình vẽ quá chằng chịt, Nam muốn đố các bạn xem có tất cả bao nhiêu giao điểm?

Một giao điểm được tính khi hai đường thẳng của một cặp kí tự cắt nhau.

**Input**

Gồm một xâu có đúng 52 kí tự in hoa. Mỗi kí tự xuất hiện đúng 2 lần.

**Output**

In ra đáp án tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| ABCCABDDEEFFGGHHIIJJKKLLMMNNOOPPQQRRSSTTUUVVWWXXYYZZ | 1 |

*Giải thích test: Chỉ có duy nhất cặp kí tự ‘A’, ‘B’ tạo ra 2 đoạn thẳng cắt nhau.*

### J03038 - ĐÁNH DẤU CHỮ CÁI

Cho một xâu ký tự S chỉ có các chữ cái Tiếng Anh viết thường. Hãy đếm xem có bao nhiêu ký tự chữ cái khác nhau trong S.

**Input:** Có duy nhất một dòng chứa xâu ký tự S, độ dài không quá 100.

**Output:** Ghi ra số ký tự chữ cái khác nhau

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| banana | 3 |

### J03039 - CHIA HẾT

Cho hai số nguyên dương a và b không quá 500 chữ số. Hãy kiểm tra xem a chia hết cho b hoặc b chia hết cho a hay không.

**Input**

Dòng đầu ghi số bộ test

Mỗi bộ test viết trên 1 dòng hai số nguyên dương, cách nhau một khoảng trống. Mỗi số có không quá 500 chữ số.

**Output**

Với mỗi test, ghi ra YES hoặc NO theo kết quả kiểm tra.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  18 7  3 123 | NO  YES |

### J03040 - BIỂN SỐ ĐẸP

Biển số xe máy được quy định gồm các thành phần:

- Hai chữ số đầu là mã quản lý theo tỉnh – thành phố (ví dụ mã của Hà Nội là 29 đến 31)
- Sau đó là một chữ cái in hoa (từ A đến Z) và một chữ số. Cặp chữ cái và chữ số này được cấp theo khu vực quận – huyện.
- Tiếp theo là dấu gạch ngang, rồi đến một dãy 5 số gồm 2 cụm: 3 chữ số đầu và hai chữ số sau, phân tách bởi dấu chấm.
 
Thông thường, người ta chỉ quan tâm đến 5 chữ số cuối. Giả sử các trường hợp sau được coi là đẹp:

- Cả 5 chữ số được sắp theo thứ tự tăng chặt từ trái qua phải.
- Cả 5 chữ số đều bằng nhau
- Ba chữ số đầu bằng nhau và hai chữ số cuối bằng nhau
- Cả 5 chữ số đều là 6 và/hoặc 8 (số lộc phát).
 
Theo quy tắc trên, các biển số sau được coi là đẹp:

- 29T1-123.79
- 29T1-555.55
- 29T1-222.33
- 29T1-686.88
 
Và các biển số sau không đẹp:

- 29T1-123.33
- 29T1-555.54
- 29T1-606.88
 
Viết chương trình kiểm tra xem các biển số xe có đẹp hay không.

**Dữ liệu vào**

- Dòng đầu ghi số bộ test, không quá 50
- Mỗi bộ test là một biển số. Dữ liệu vào đảm bảo biển số được viết đúng quy định.
 
**Kết quả**

- In ra kết quả kiểm tra với từng bộ test
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 7  29T1–123.45  29T1–555.55  29T1–222.33  29T1–686.88  29T1–123.33  29T1–555.54  29T1–606.88 | YES  YES  YES  YES  NO  NO  NO |

### J07003 - TÁCH ĐÔI VÀ TÍNH TỔNG

Cho một số nguyên dương không quá 200 chữ số. Mỗi bước tách số nguyên thành hai nửa: **nửa đầu** là n/2 chữ số đầu tiên, **nửa sau** là phần còn lại (trong đó n là số chữ số của số ban đầu, nếu n lẻ thì phép chia 2 sẽ tính phần nguyên). Sau đó thực hiện tính tổng của hai nửa này.

Lặp lại các bước trên cho đến khi kết quả chỉ còn là số có 1 chữ số.

Hãy thực hiện tính toán và in kết quả của từng bước.

**Input - file văn bản DATA.in**

Chỉ có một số nguyên dương không quá 200 chữ số.

**Output**

Ghi ra kết quả từng bước, mỗi bước trên một dòng. Dừng lại khi kết quả chỉ còn 1 chữ số.

**Ví dụ**

 | **DATA.in** | **Ouput** |
|---|---|
| 123456 | 579  84  12  3 |

 ***Gợi ý: Sử dụng lớp BigInteger***

### J07008 - DÃY CON TĂNG DẦN

Cho dãy số a\[\] có n phần tử là các số nguyên dương khác nhau từng đôi một. Hãy liệt kê tất cả các dãy con có từ 2 phần tử trở lên của dãy a\[\] thỏa mãn tính chất tăng dần.

Dãy con tạo được bằng cách lấy ra các phần tử trong dãy a\[\] nhưng vẫn giữ nguyên thứ tự ban đầu.

Coi mỗi dãy con như một xâu ký tự với các phần tử cách nhau một khoảng trống, hãy liệt kê theo thứ tự tử điển.

**Input - file DAYSO.in**

- Dòng đầu ghi số n (không quá 20)
- Dòng thứ 2 ghi n số của dãy a\[\]. Các số khác nhau từng đôi một và có giá trị không quá 100.
 
**Output**

Ghi ra lần lượt các dãy con tăng dần theo thứ tự từ điển.

**Ví dụ**

 | **DAYSO.in** | **Output** |
|---|---|
| 4  6 3 7 11 | 3 11  3 7  3 7 11  6 11  6 7  6 7 11  7 11 |

 ***Gợi ý: Sử dụng duyệt xâu nhị phân để liệt kê các dãy con tăng dần, mỗi lần ghép kết quả thành dạng String, sau đó đưa vào một ArrayList và sắp xếp theo thứ tự từ điển.***

## MẢNG

### J02004 - MẢNG ĐỐI XỨNG

Nhập một dãy số nguyên có n phần tử (n không quá 100, các phần tử trong dãy không quá 109). Hãy viết chương trình kiểm tra xem dãy có phải đối xứng hay không. Nếu đúng in ra YES, nếu sai in ra NO.

**Dữ liệu vào:** Dòng đầu ghi số bộ test, mỗi bộ test gồm hai dòng. Dòng đầu là số phần tử của dãy, dòng sau ghi ra dãy đó, mỗi số cách nhau một khoảng trống.

**Kết quả:** In ra kết quả kiểm tra.

 | **Input** | **Ouput** |
|---|---|
| 2  4  1 4 4 1  5  1 5 5 5 3 | YES  NO |

### J02005 - GIAO CỦA HAI DÃY SỐ

Cho dãy số a\[\] có n phần tử và dãy số b\[\] có m phần tử là các số nguyên dương nhỏ hơn 1000. Gọi tập hợp A là tập các số khác nhau trong a\[\], tập hợp B là tập các số khác nhau trong b\[\].

Hãy tìm tập giao của A và B.

**Input**

Dòng đầu ghi 2 số n và m (1 &lt; n,m &lt;100).

Dòng thứ 2 ghi n số của a\[\].

Dòng thứ 3 ghi m số của b\[\].

Các số đều dương và nhỏ hơn 1000.

**Output**

Ghi tập giao của A và B trên một dòng theo thứ tự từ nhỏ đến lớn.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 6  1 2 3 4 5  3 4 5 6 7 8 | 3 4 5 |

### J02006 - HỢP CỦA HAI DÃY SỐ

Cho dãy số a\[\] có n phần tử và dãy số b\[\] có m phần tử là các số nguyên dương nhỏ hơn 1000. Gọi tập hợp A là tập các số khác nhau trong a\[\], tập hợp B là tập các số khác nhau trong b\[\].

Hãy tìm **hợp** của A và B

**Input**

Dòng đầu ghi 2 số n và m (1 &lt; n,m &lt;100).

Dòng thứ 2 ghi n số của a\[\].

Dòng thứ 3 ghi m số của b\[\].

Các số đều dương và nhỏ hơn 1000.

**Output**

Ghi ra hợp của hai tập A và B theo thứ tự tăng dần.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5 6  1 2 3 4 5  3 4 5 6 7 8 | 1 2 3 4 5 6 7 8 |

 

Giới hạn thời gian: 1s

### J02007 - ĐẾM SỐ LẦN XUẤT HIỆN

Cho dãy số A có n phần tử chỉ bao gồm các số nguyên dương (không quá 105). Hãy đếm xem mỗi số xuất hiện bao nhiêu lần.

**Dữ liệu vào:** Dòng đầu tiên ghi số bộ test. Với mỗi bộ test: dòng đầu ghi số n (không quá 100); dòng tiếp theo ghi n số của dãy.

**Kết quả: Với mỗi bộ test ghi ra thứ tự bộ test, sau đó lần lượt là các số nguyên tố trong dãy **theo thứ tự** **xuất hiện trong dãy** và số lần xuất hiện của nó.

 | **Input** | **Output** |
|---|---|
| 1  10  1 7 2 8 3 3 2 1 3 2 | Test 1:  1 xuat hien 2 lan  7 xuat hien 1 lan  2 xuat hien 3 lan  8 xuat hien 1 lan  3 xuat hien 3 lan |

### J02008 - BỘI SỐ NHỎ NHẤT CỦA N SỐ NGUYÊN DƯƠNG ĐẦU TIÊN

Cho số tự nhiên n. Nhiệm vụ của bạn là tìm số nguyên nhỏ nhất chia hết cho 1, 2, .., n.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- T dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một số tự nhiên n.
- T thỏa mãn ràng buộc: 1≤T≤104; n không quá 100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  3  5 | 6  60 |

### J02009 - XẾP HÀNG

Tại sân bay, mọi người đang làm thủ tục để check in. Có tất cả N vị khách. Vị khách thứ i tới làm thủ tục tại thời điểm T\[i\] và cần D\[i\] thời gian để check-in xong.

Các bạn hãy xác định xem thời điểm nào tất cả các vị khách làm xong thủ tục để lên máy bay?

**Input**

Dòng đầu tiên là số nguyên dương N (N ≤ 100).

N dòng tiếp theo, mỗi dòng gồm 2 số nguyên cho biết thời điểm đến của vị khách thứ i và thời gian vị khách này làm xong thủ tục check in. Các giá trị này không vượt quá 106.

**Output**

In ra đáp án tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  2 1  8 3  5 7 | 15 |

Giải thích test:

Vị khách đầu tiên tới lúc t = 2 và mất 1 đơn vị thời gian để check in. Vị khách thứ 2 tới lúc t = 5, và làm xong thủ tục tại thời điểm t = 12. Vị khách thứ 3 tới lúc t = 8, nhưng phải chờ tới thời điểm t = 12 để check in, hoàn thành tại thời điểm t = 15.

### J02010 - SẮP XẾP ĐỔI CHỖ TRỰC TIẾP

Hãy thực hiện thuật toán sắp xếp đổi chỗ trực tiếp trên dãy N số nguyên. Ghi ra các bước thực hiện thuật toán. **Dữ liệu vào:** Dòng 1 ghi số N (không quá 100). Dòng 2 ghi N số nguyên dương (không quá 100). **Kết quả:** Ghi ra màn hình từng bước thực hiện thuật toán. Mỗi bước trên một dòng, các số trong dãy cách nhau đúng một khoảng trống.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 4  5 7 3 2 | Buoc 1: 2 7 5 3  Buoc 2: 2 3 7 5  Buoc 3: 2 3 5 7 |

### J02011 - SẮP XẾP CHỌN

Hãy thực hiện thuật toán sắp xếp chọn trên dãy N số nguyên. Ghi ra các bước thực hiện thuật toán.

**Dữ liệu vào:** Dòng 1 ghi số N (không quá 100). Dòng 2 ghi N số nguyên dương (không quá 100).

**Kết quả:** Ghi ra màn hình từng bước thực hiện thuật toán. Mỗi bước trên một dòng, các số trong dãy cách nhau đúng một khoảng trống.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 4  5 7 3 2 | Buoc 1: 2 7 3 5  Buoc 2: 2 3 7 5  Buoc 3: 2 3 5 7 |

### J02012 - SẮP XẾP CHÈN

Hãy thực hiện thuật toán sắp xếp chèn trên dãy N số nguyên. Ghi ra các bước thực hiện thuật toán.

**Dữ liệu vào:** Dòng 1 ghi số N (không quá 100). Dòng 2 ghi N số nguyên dương (không quá 100).

**Kết quả:** Ghi ra màn hình từng bước thực hiện thuật toán. Mỗi bước trên một dòng, các số trong dãy cách nhau đúng một khoảng trống.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 4  5 7 3 2 | Buoc 0: 5  Buoc 1: 5 7  Buoc 2: 3 5 7  Buoc 3: 2 3 5 7 |

### J02013 - SẮP XẾP NỔI BỌT

Hãy thực hiện thuật toán sắp xếp nổi bọt trên dãy N số nguyên. Ghi ra các bước thực hiện thuật toán.

**Dữ liệu vào:** Dòng 1 ghi số N (không quá 100). Dòng 2 ghi N số nguyên dương (không quá 100).

**Kết quả:** Ghi ra màn hình từng bước thực hiện thuật toán. Mỗi bước trên một dòng, các số trong dãy cách nhau đúng một khoảng trống.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 4  5 3 2 7 | Buoc 1: 3 2 5 7  Buoc 2: 2 3 5 7 |

### J02014 - ĐIỂM CÂN BẰNG

Cho dãy số A\[\] gồm có N phần tử nguyên dương. Phần tử thứ i được gọi là điểm cân bằng của dãy số nếu như tổng các số bên trái bằng tổng các số bên phải của nó.

Nhiệm vụ của bạn là điểm cân bằng đầu tiên của dãy A\[\] cho trước. Nếu không có đáp án, in ra -1.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test gồm số nguyên N (1≤ N ≤ 100 000), số lượng phần tử trong dãy số ban đầu.
- Dòng tiếp theo gồm N số nguyên A\[i\] (-1000 ≤ A\[i\] ≤ 1000).
 
**Output:**

- Với mỗi test, in ra trên một dòng vị trí của điểm cân bằng tìm được.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  7  -7 1 5 2 -4 3 0  5  1 2 3 4 5 | 4  -1 |

### J02016 - BỘ BA SỐ PYTAGO

Cho dãy số A\[\] gồm có N phần tử. Một bộ 3 số (a, b, c) được gọi là bộ ba số Pytago nếu như a^2 + b^2 = c^2.

Nhiệm vụ của bạn là kiểm tra xem có tồn tại bộ ba số Pytago trong dãy số A\[\] hay không?

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test gồm số nguyên N (1≤ N ≤5000).
- Dòng tiếp theo gồm N số nguyên A\[i\] (1 ≤ A\[i\] ≤ 109).
 
**Output:**

- Với mỗi test, in ra trên một dòng “YES” nếu tìm được, và “NO” trong trường hợp ngược lại.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  5  3 1 4 6 5  3  1 1 1 | YES  NO |

### J02017 - THU GỌN DÃY SỐ

Cho dãy số A\[\] chỉ bao gồm các số nguyên dương. Người ta thu gọn dần dãy số bằng cách loại bỏ các cặp phần tử kề nhau mà có tổng là chẵn. Sau khi cặp phần tử đó bị loại ra thì dãy số được dồn lại. Cứ tiếp tục như vậy cho đến khi không còn cặp phần tử nào kề nhau có tổng chẵn nữa.

Hãy tính xem cuối cùng dãy A\[\] còn bao nhiêu phần tử.

**Input**

Dòng đâu ghi số N là số phần tử của dãy (1 ≤ N ≤ 105 tức là dãy A có thể có đến 10 nghìn phần tử).

Dòng tiếp theo ghi N số của dãy A (1 ≤ A\[i\] ≤ 100).

**Output**

Ghi ra trên một dòng số phần tử còn lại trong dãy A\[\].

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  2 3 4 5 6 | 5 |
| **Input** | **Output** |
| 10  1 5 5 8 6 4 3 5 9 3 | 2 |

### J02019 - TỔNG ƯỚC SỐ - 2

Cho hai số nguyên dương a,b. Hãy đếm xem trong đoạn \[a,b\] có bao nhiêu số có tổng các ước số (không tính chính nó) lớn hơn giá trị của nó.

Ví dụ: số 12 có tổng ước số là 1 + 2 + 3 + 4 + 6 = 16 &gt; 12.

**Input**

Chỉ có hai số a và b (1 &lt;= a &lt;= b &lt;= 106).

**Output**

Ghi ra số lượng các số thỏa mãn.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1 50 | 9 |

### J02020 - LIỆT KÊ TỔ HỢP - 1

Cho hai số N và K (2 &lt; K &lt; N &lt; 10).

Sử dụng thuật toán sinh kế tiếp hoặc quay lui, hãy liệt kê tất cả các tổ hợp chập K phần tử của N số nguyên dương đầu tiên theo thứ tự tăng dần.

**Input**

Chỉ có một dòng ghi hai số N và K.

**Output**

Ghi ra lần lượt các tổ hợp, mỗi tổ hợp trên một dòng, các phần tử cách nhau một khoảng trống. Dòng cuối cùng ghi ra tổng số tổ hợp theo mẫu như trong ví dụ.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 3 | 1 2 3  1 2 4  1 2 5  1 3 4  1 3 5  1 4 5  2 3 4  2 3 5  2 4 5  3 4 5  Tong cong co 10 to hop |

### J02021 - LIỆT KÊ TỔ HỢP - 2

Cho hai số N và K (2 &lt; K &lt; N &lt; 10).

Sử dụng thuật toán sinh kế tiếp hoặc quay lui, hãy liệt kê tất cả các tổ hợp chập K phần tử của N số nguyên dương đầu tiên theo thứ tự tăng dần.

**Input**

Chỉ có một dòng ghi hai số N và K.

**Output**

Ghi ra lần lượt các tổ hợp, các giá trị số trong tổ hợp viết sát cạnh nhau, các tổ hợp cách nhau một khoảng trống. Dòng cuối cùng ghi ra tổng số tổ hợp theo mẫu như trong ví dụ.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 3 | 123 124 125 134 135 145 234 235 245 345  Tong cong co 10 to hop |

### J02022 - SỐ XA CÁCH

Cho số nguyên dương N (2 &lt; N &lt;10). Một số nguyên dương K có N chữ số được gọi là số xa cách nếu thỏa mãn:

- K không chứa chữ số 0
- Tất cả các chữ số từ 1 đến N đều xuất hiện trong K đúng 1 lần
- Không có hai chữ số liên tiếp nào trong K có hiệu bằng 1.
 
Hãy liệt kê tất cả các số thỏa mãn theo thứ tự tăng dần.

**Input**

- Dòng đầu ghi số bộ test (không quá 10)
- Mỗi bộ test là 1 số nguyên dương N (2 &lt; N &lt; 10)
 
**Output**

Liệt kê tất cả các số thỏa mãn, mỗi số trên một dòng.

Sau mỗi test in ra một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  3  4 | 2413  3142 |

### J02023 - LỰA CHỌN THAM LAM

Cho hai số nguyên dương N và S. Hãy lựa chọn các chữ số phù hợp để tạo ra số nhỏ nhất và số lớn nhất có N chữ số sao cho tổng chữ số đúng bằng S.

**Input**

Chỉ có một dòng ghi hai số N và S. (0 &lt; N &lt;= 100; 0 &lt;= S &lt;= 900)

**Output**

Ghi ra hai số nhỏ nhất và lớn nhất tìm được, cách nhau một khoảng trống.

Nếu không thể tìm được thì ghi ra “-1 -1”

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3 20 | 299 992 |
| 2 900 | -1 -1 |
| 3 0 | -1 -1 |

### J02024 - DÃY CON CÓ TỔNG LẺ

Cho dãy số A\[\] có N phần tử là các số nguyên dương khác nhau từng đôi một.

Hãy sắp xếp dãy theo thứ tự giảm dần, sau đó liệt kê tất cả các dãy con (đúng thứ tự trước sau) của A\[\] có tổng các phần tử là số lẻ.

Các dãy con được liệt kê theo thứ tự từ điển tăng dần.

**Input**

Dòng đầu ghi số bộ test, mỗi test có 2 dòng:

- Dòng đầu ghi số N (2 &lt; N &lt;15)
- Dòng thứ 2 ghi N số của dãy A\[\], các số đều nguyên dương, nhỏ hơn 100 và khác nhau từng đôi một.
 
**Output**

Với mỗi test, liệt kê tất cả các dãy con có tổng các phần tử là số lẻ theo thứ tự từ điển tăng dần, mỗi dãy con trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  4  2 3 4 5 | 3  3 2  4 3  4 3 2  5  5 2  5 4  5 4 2 |

### J02025 - DÃY CON CÓ TỔNG NGUYÊN TỐ

Cho dãy số A\[\] có N phần tử là các số nguyên dương khác nhau từng đôi một. Hãy liệt kê tất cả các dãy con của A\[\] có tổng các phần tử là số nguyên tố.

Các dãy con được liệt kê theo thứ tự từ điển tăng dần.

**Input**

Dòng đầu ghi số bộ test, mỗi test có 2 dòng:

- Dòng đầu ghi số N (2 &lt; N &lt;15)
- Dòng thứ 2 ghi N số của dãy A\[\], các số đều nguyên dương, nhỏ hơn 100 và khác nhau từng đôi một.
 
**Output**

Với mỗi test, liệt kê tất cả các dãy con có tổng các phần tử là số nguyên tố theo thứ tự từ điển tăng dần, mỗi dãy con trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  4  3 2 5 4 | 2  3  3 2  4 3  5  5 2  5 4 2 |

### J02026 - DÃY CON CÓ K PHẦN TỬ TĂNG DẦN

Cho dãy số A\[\] có N phần tử là các số nguyên dương khác nhau từng đôi một và một số K &lt; N.

Hãy liệt kê tất cả các dãy con khác nhau có K phần tử của A\[\], mỗi dãy đều được sắp xếp theo thứ tự tăng dần.

Các dãy con được liệt kê lần lượt theo thứ tự từ điển.

**Input**

Dòng đầu ghi số bộ test, mỗi test có 2 dòng:

- Dòng đầu ghi hai số N và K (2 &lt; K &lt; N &lt;15)
- Dòng thứ 2 ghi N số của dãy A\[\], các số đều nguyên dương, nhỏ hơn 100 và khác nhau từng đôi một.
 
**Output**

Với mỗi test, liệt kê tất cả các dãy con thỏa mãn, mỗi dãy con trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  4 3  3 2 5 4 | 2 3 4  2 3 5  2 4 5  3 4 5 |

### J02027 - KHOẢNG CÁCH NHỎ HƠN K

Cho mảng A\[\] gồm n số nguyên dương và số K. Hãy đếm số các cặp phần tử có hiệu nhỏ hơn K. Ví dụ A\[\] = {1, 10, 4, 2 }, K=3 ta nhận được kết quả là 2 tương ứng với các cặp (1, 2), (4, 2).

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Mỗi bộ test gồm hai dòng: dòng đầu tiên ghi số n và số K; dòng tiếp theo là n số A\[i\] ; các số được viết cách nhau một vài khoảng trống.
- T, n, k, A\[i\] thỏa mãn ràng buộc: 1 ≤ T ≤ 100; 1 ≤ n ≤ 104; 1 ≤ k ≤ 103; 1 ≤ A\[i\] ≤ 105.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2    4 3    1 10 4 2    3 5    2 3 4 | 2    3 |

### J02028 - DÃY CON LIÊN TIẾP TỔNG BẰNG K

Cho dãy số A\[\] gồm có N phần tử không âm và số K.

Nhiệm vụ của bạn là hãy xác định xem có tìm được 1 dãy con liên tiếp mà tổng các phần tử bằng K hay không?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test gồm số nguyên N và K (1≤ N ≤ 100 000, 0 ≤ K ≤ 1018).

Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 109).

**Output:**

Với mỗi test, in ra trên một dòng là đáp án thu được. Nếu có hãy in ra “YES”. Nếu không tìm được đáp án, in ra “NO”.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  6 33  1 4 20 3 10 5  7 7  1 4 0 0 3 10 5  2 0  1 4 | YES  YES  NO |

**Giải thích test 1:**

20+3+10 = 33

### J02033 - ĐẢO DẤU

Cho một mảng a gồm n phần tử và 1 số k, bạn phải thực hiện đúng k phép biến đổi, với mỗi phép biến đổi, bạn phải chọn 1 số a\[i\] và thay thế nó bằng số -a\[i\].

Hãy tìm cách thực hiện k phép biến đổi sao cho tổng các phần tử của mảng a sau khi biến đổi là lớn nhất.

**Input**

Dòng đầu tiên là số n (1 ≤ n ≤ 105) và k (0 ≤ k ≤ 105)

Dòng tiếp theo gồm n số a\[1\], a\[2\], ... a\[n\] ( -105 ≤ a\[i\] ≤ 105)

**Output:**

1 dòng duy nhất là tổng lớn nhất của các phần tử của mảng a sau khi thực hiện phép biến đổi.

**Ví dụ :**

 | **Input** | **Output** |
|---|---|
| 3 1  4 6 2 | 8 |

Giải thích :

Ta sử dụng phép biến đổi với phần tử a\[3\] = 2.

Khi đó mảng trở thành \[4, 6, -2\] , tổng = 8

### J02034 - BỔ SUNG DÃY SỐ

Cho dãy số có N số nguyên dương khác nhau đã được sắp xếp tăng dần. Hãy liệt kê các số còn thiếu để có đủ các số trong khoảng từ 1 đến số lớn nhất trong dãy ban đầu.

**Input:**

- Dòng đầu ghi số N là số con số được đếm (1 ≤ N ≤ 100)
- Các dòng tiếp theo ghi đủ N số A\[i\] theo thứ tự tăng dần (1 ≤ A\[i\] ≤ 200). Các số phân cách bởi khoảng trống hoặc xuống dòng.
 
**Kết quả:**

- Nếu đã có đủ các số thì ghi ra **Excellent!**
- Nếu chưa đủ thì lần lượt liệt kê các số còn thiếu, mỗi số trên một dòng.
 
**Ví dụ:**

 | **Input 1** | **Output 1** |
|---|---|
| 4  1 2 3 5 | 4 |
| **Input 2** | **Output 2** |
| 7  4 5 7 8 9  10 11 | 1  2  3  6 |
| **Input 3** | **Output 3** |
| 5  1 2 3  4  5 | Excellent! |

### J02035 - QUAY PHẢI

Dãy số A\[\] gồm N phần tử là các số nguyên và đã được sắp xếp tăng dần. Các phần tử của dãy A\[\] có thể giống nhau. Sau đó ta thực hiện quay vòng phải, mỗi lần lấy một số ở cuối dãy đưa lên đầu dãy.

Cho trạng thái dãy số của A\[\] sau khi đã thực hiện quay vòng K lần. Hãy tìm K.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng thứ nhất đưa vào số N; dòng tiếp theo đưa vào N số của mảng A\[\]các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤ N≤107; 0≤ A\[i\]≤1018.
 
**Output:**

- Đưa ra số lần quay vòng K của mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    5    5 1 2 3 4    5    1 2 3 4 5 | 1    0 |

### J02036 - ƯỚC SỐ CHUNG LỚN NHẤT

Gọi **gcd(a,b)** là thao tác tính ước số chung lớn nhất của hai số nguyên a,b.

Cho dãy số A\[\] nguyên dương có N phần tử. Hãy xây dựng dãy số B có N+1 phần tử sao cho **gcd(B\[i\], B\[i+1\]) = A\[i\]** với mọi i thỏa mãn 1 ≤ i ≤ n. Vì có rất nhiều dãy số B\[\] thỏa mãn, nên bạn cần tìm được dãy số có tổng các phần tử là nhỏ nhất.

**Input**

- Dòng đầu tiên là số lượng bộ test T (1 ≤ T ≤ 10).
- Mỗi test bắt đầu bằng số nguyên N (2 ≤ N ≤ 1000).
- Dòng tiếp theo gồm N số nguyên A\[i\] (1 ≤ A\[i\] ≤ 10 000).
 
**Output**

- Với mỗi test in ra dãy số B\[\] trên một dòng.
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2  3  1 2 3  3  5 10 5 | 1 2 3 6 3  5 10 10 5 |

### J02101 - IN MA TRẬN

Cho ma trận vuông A\[N\]\[N\]. Hãy in các phần tử thuộc ma trận theo kiểu từ trái qua phải ở hàng đầu tiên, sau đó từ phải qua trái ở hàng thứ hai ...

Xem hình ví dụ để hiểu rõ hơn.

![Alt text](./img/J02101_1.png)

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào N là cấp của ma trận A\[N\]\[N\]; dòng tiếp theo đưa vào N×N số A\[i\]\[j\] ; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\]\[j\] thỏa mãn ràng buộc: 1≤ T ≤100; 1≤ N ≤100; 1≤ A\[i\]\[j\] ≤150.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 2    3    45 48 54 21 89 87 70 78 15    2    25 27 23 21 | 45 48 54 87 89 21 70 78 15    25 27 21 23 |

### J02102 - MA TRẬN XOẮN ỐC TĂNG DẦN

Cho ma trận vuông A cỡ N\*N chỉ bao gồm các số nguyên dương không quá 1000. Hãy sắp đặt các giá trị trong ma trận A sao cho các số được điền lần lượt theo kiểu xoắn ốc tăng dần, theo chiều kim đồng hồ.

**Input**

Dòng đầu ghi số N (2 &lt; N &lt; 20).

N dòng tiếp theo ghi ma trận A, các giá trị nguyên dương và không quá 1000.

**Output**

Ghi ra ma trận kết quả

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  3 6 1  8 7 9  4 12 5 | 1 3 4  9 12 5  8 7 6 |

### J02103 - TÍCH MA TRẬN VỚI CHUYỂN VỊ CỦA NÓ

Cho ma trận A chỉ gồm các số nguyên dương cấp N\*M. Hãy viết chương trình tính tích của A với ma trận chuyển vị của A.

**Dữ liệu vào:** Dòng đầu tiên ghi số bộ test. Với mỗi bộ test: Dòng đầu tiên ghi hai số n và m là bậc của ma trân a; n dòng tiếp theo, mỗi dòng ghi m số của một dòng trong ma trận A.

**Kết quả:** Với mỗi bộ test ghi ra thứ tự bộ test, sau đó đến ma trận tích tương ứng, mỗi số cách nhau đúng một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  2 2  1 2  3 4 | Test 1:  5 11  11 25 |

### J02104 - DANH SÁCH CẠNH

Cho đồ thị vô hướng G=&lt;V, E&gt; được biểu diễn dưới dạng ma trận kề. Hãy viết chương trình thực hiện chuyển đổi biểu diễn đồ thị dưới dạng danh sách cạnh.

**Input:**

- Dòng đầu tiên ghi số N là số đỉnh của đồ thị **(không quá 1000)**
- N dòng tiếp theo đưa vào các phần tử của ma trận kề.
 
**Output:**

- Đưa ra danh sách cạnh tương ứng theo khuôn dạng trong ví dụ dưới đây.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 6  0 1 1 0 1 0  1 0 1 0 1 0  1 1 0 1 0 0  0 0 1 0 1 1  1 1 0 1 0 1  0 0 0 1 1 0 | (1,2)  (1,3)  (1,5)  (2,3)  (2,5)  (3,4)  (4,5)  (4,6)  (5,6) |

### J02105 - DANH SÁCH KỀ

Cho đồ thị vô hướng G=&lt;V, E&gt; được biểu diễn dưới dạng ma trận kề. Hãy viết chương trình thực hiện chuyển đổi biểu diễn đồ thị dưới dạng danh sách kề.

**Input:**

- Dòng đầu tiên ghi số N là số đỉnh của đồ thị **(không quá 1000)**
- N dòng tiếp theo đưa vào các phần tử của ma trận kề.
 
**Output:**

- Đưa ra danh sách kề tương ứng theo khuôn dạng trong ví dụ dưới đây.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 6  0 1 1 0 1 0  1 0 1 0 1 0  1 1 0 1 0 0  0 0 1 0 1 1  1 1 0 1 0 1  0 0 0 1 1 0 | List(1) = 2 3 5  List(2) = 1 3 5  List(3) = 1 2 4  List(4) = 3 5 6  List(5) = 1 2 4 6  List(6) = 4 5 |

### J02106 - MA TRẬN NHỊ PHÂN

Cho ma trận A\[\] có N hàng và 3 cột, trong đó các vị trí là các giá trị nhị phân (0 hoặc 1). Hãy đếm xem có bao nhiêu hàng mà số lượng số 1 nhiều hơn số lượng số 0.

**Input**

Dòng đầu ghi số nguyên dương N (không quá 1000).

N dòng tiếp theo, mỗi dòng ghi 3 giá trị nhị phân.

**Output**

Ghi ra số dòng mà số lượng số 1 nhiều hơn số lượng số 0.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  1 1 0  1 1 1  1 0 0 | 2 |
| 2  1 0 0  0 1 1 | 1 |

## CHƯA PHÂN LOẠI

### J020356 - LỰA CHỌN THAM LAM

Cho hai số nguyên dương N và S. Hãy lựa chọn các chữ số phù hợp để tạo ra số nhỏ nhất và số lớn nhất có N chữ số sao cho tổng chữ số đúng bằng S.

**Input**

Chỉ có một dòng ghi hai số N và S. (0 &lt; N &lt;= 100; 0 &lt;= S &lt;= 900)

**Output**

Ghi ra hai số nhỏ nhất và lớn nhất tìm được, cách nhau một khoảng trống.

Nếu không thể tìm được thì ghi ra “-1 -1”

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3 20 | 299 992 |
| 2 900 | -1 -1 |
| 3 0 | -1 -1 |

### J07006 - SỐ KHÁC NHAU TRONG FILE - 3

Cho file **nhị phân** DATA.in có một ArrayList&lt;Integer&gt;, giá trị các số đều lớn hơn hoặc bằng 0 và nhỏ hơn 1000. Có không quá 106 số trong danh sách.

Hãy liệt kê các số khác nhau xuất hiện trong file và số lần xuất hiện của từng số đó.

**Input**

File DATA.in lưu một ArrayList&lt;Integer&gt; theo kiểu Object.

**Output**

Ghi ra các số khác nhau và số lần xuất hiện theo thứ tự tăng dần

**Ví dụ:**

 | **DATA.in** | **Output** |
|---|---|
| File nhị phân theo mô tả đề bài | Liệt kê các số tăng dần. Ví dụ:  10 2  23 1  24 1  25 4 |

### J07033 - DANH SÁCH SINH VIÊN TRONG FILE - 1

Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100, có thể chưa chuẩn
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 30)
 
Hãy nhập danh sách sinh viên và liệt kê danh sách sắp xếp theo mã sinh viên tăng dần (thứ tự từ điển). Chú ý: cần chuẩn hóa họ tên.

**Input – file SINHVIEN.in**

Dòng đầu ghi số sinh viên (không quá 1000)

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

**Output**

Với mỗi truy vấn, liệt kê danh sách sinh viên của lớp đó theo mẫu như trong ví dụ. Mỗi sinh viên ghi trên một dòng, các thông tin cách nhau một khoảng trống. Yêu cầu sắp xếp theo mã sinh viên tăng dần.

**Ví dụ**

 | **SINHVIEN.in** | **Output** |
|---|---|
| 2  B15DCKT150  NGUYEN NGOC SON  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  NguyeN TrONg Tung  D15CQKT02-B  sv4@stu.ptit.edu.vn | B15DCKT150 Nguyen Ngoc Son D15CQKT02-B sv3@stu.ptit.edu.vn  B15DCKT199 Nguyen Trong Tung D15CQKT02-B sv4@stu.ptit.edu.vn |

## KHAI BÁO LỚP VÀ ĐỐI TƯỢNG

### J04001 - KHAI BÁO LỚP POINT

Khai báo lớp Point (điểm trong không gian hai chiều) có mô tả như sau:

![Alt text](./img/J04001_1.png)

Viết chương trình nhập vào hai điểm p1, p2 và tính khoảng cách hai điểm đó.

**Input**

- Dòng đầu ghi số bộ test, không quá 20.
- Mỗi bộ test có 4 số thực lần lượt là tọa độ của 2 điểm A và B, giá trị tuyệt đối không quá 1000.
 
**Ouput**

Với mỗi bộ test, viết ra khoảng cách giữa 2 điểm với 4 chữ số phần thập phân.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  0 0 0 5  0 199 5 6 | 5.0000  193.0648 |

### J04002 - KHAI BÁO LỚP HÌNH CHỮ NHẬT

Viết chương trình khai báo lớp Rectange với các thuộc tính và phương thức như sau:

 | **Rectange** |  |
|---|---|
| \- width: double | Chiều rộng hình chữ nhật |
| \- height: double | Chiều dài hình chữ nhật |
| \- color: String | Màu hình chữ nhật |
| \+ Rectange() | Tạo HCN có c.dài = 1, c.rộng = 1 |
| \+ Rectange(width: double,  height: double, color: String) | Tạo HCN có c.dài, c.rộng xác định qua tham số |
| \+ getWidth() :double | Trả về chiều rộng |
| \+ setWidth(width:double): void | Thiết lập chiều rộng mới |
| \+ getHeight(): double | Trả về chiều dài |
| \+ setHeight(height:double): void | Thiết lập chiều dài mới |
| \+ getColor(): String | Trả về màu của HCN |
| \+ setColor(color): void | Thiết lập màu mới cho HCN |
| \+ findArea(): double | Tính và trả về diện tích HCN |
| \+ findPerimeter(): double | Tính và trả về chu vi HCN |

Viết chương trình nhập vào giá trị độ dài hai cạnh của hình chữ nhật và màu sắc. In ra thông tin về chu vi, diện tích và màu sắc (đã đưa về dạng chuẩn trong đó ký tự đầu viết hoa, các ký tự sau viết thường) của hình chữ nhật đó.

**Input**

Gồm 2 số nguyên là độ dài 2 cạnh hình chữ nhật và một xâu ký tự (không có khoảng trống) mô tả màu sắc.

**Output**

Nếu hình chữ nhật là hợp lệ (các cạnh đều nguyên dương) thì in ra 3 thông tin: chu vi, diện tích, màu sắc, mỗi thông tin cách nhau một khoảng trống.

Nếu dữ liệu không hợp lệ in ra INVALID

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 10 2 RED | 24 20 Red |

### J04003 - PHÂN SỐ

Viết chương trình khai báo lớp Phân số gồm hai thuộc tính private là tử số và mẫu số. Các giá trị đều nguyên dương và không quá 18 chữ số.

Sau đó thực hiện nhập vào một phân số và in ra phân số đó ở dạng tối giản.

**Input**

Có hai số nguyên dương lần lượt là tử số và mẫu số.

**Output**

Ghi ra phân số tối giản như trong ví dụ

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 123 456 | 41/152 |

### J04004 - TỔNG PHÂN SỐ

Viết chương trình xây dựng lớp Phân số gồm hai phần tử là tử số và mẫu số. Các giá trị đều nguyên dương và không quá 9 chữ số.

Sau đó thực hiện nhập vào hai phân số p và q. Tính tổng p + q, rút gọn và in ra kết quả.

**Input**

Có bốn số nguyên dương lần lượt là tử số và mẫu số của p rồi đến q.

**Output**

Ghi ra phân số tổng p + q ở dạng tối giản như trong ví dụ

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 123 456 12 34 | 1609/2584 |

### J04005 - KHAI BÁO LỚP THÍ SINH

Viết chương trình khai báo lớp Thí Sinh gồm các thông tin: Họ tên, Ngày sinh, Điểm môn 1, Điểm môn 2, Điểm môn 3 và Tổng điểm.

Đọc thông tin 1 thí sinh từ bàn phím và in ra màn hình 3 thông tin: Họ tên, Ngày sinh, Tổng điểm.

**Input**

Gồm 5 dòng lần lượt, mỗi dòng ghi 1 thông tin: Họ tên, Ngày sinh, Điểm môn 1, Điểm môn 2, Điểm môn 3. Họ tên không quá 50 chữ cái, Ngày sinh viết đúng chuẩn dd/mm/yyyy. Các giá trị điểm là số thực (float).

**Output**

Ghi ra Họ tên, Ngày sinh và Tổng điểm. Mỗi thông tin cách nhau một khoảng trống. Điểm được ghi ra với 1 số sau dấu phẩy.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| Nguyen Hoang Ha  11/10/2001  4.5  10.0  5.5 | Nguyen Hoang Ha 11/10/2001 20.0 |

### J04006 - KHAI BÁO LỚP SINH VIÊN

Viết chương trình khai báo lớp Sinh Viên gồm các thông tin: Mã SV, Họ tên, Lớp, Ngày sinh và Điểm GPA (dạng số thực float). Hàm khởi tạo không có tham số, gán các giá trị thuộc tính ở trạng thái mặc định (xâu ký tự rỗng, giá trị số bằng 0).

Đọc thông tin 1 sinh viên từ bàn phím (không có mã sinh viên) và in ra màn hình. Trong đó Mã SV được gán là **B20DCCN001**. Ngày sinh được chuẩn hóa về dạng dd/mm/yyyy.

**Input**

Gồm 4 dòng lần lượt là Họ tên, Lớp, Ngày sinh và Điểm GPA.

Trong đó:

- Họ tên không quá 30 chữ cái.
- Lớp theo đúng định dạng thường dùng ở PTIT
- Ngày sinh có đủ 3 phần ngày tháng năm nhưng có thể chưa đúng chuẩn dd/mm/yyyy.
- Điểm GPA đảm bảo trong thang điểm 4 với 2 nhiều nhất 2 số sau dấu phẩy.
 
**Output**

Ghi thông tin sinh viên trên 1 dòng, mỗi thông tin cách nhau 1 khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| Nguyen Hoa Binh  D20CQCN04-B  2/2/2002  2 | B20DCCN001 Nguyen Hoa Binh D20CQCN04-B 02/02/2002 2.00 |

### J04007 - KHAI BÁO LỚP NHÂN VIÊN

Một nhân viên làm việc trong công ty được lưu lại các thông tin sau:

- Mã nhân viên: được gán giá trị là 00001
- Họ tên: Xâu ký tự không quá 40 chữ cái.
- Giới tính: Nam hoặc Nu
- Ngày sinh: đúng theo chuẩn dd/mm/yyyy
- Địa chỉ: Xâu ký tự không quá 100 chữ cái
- Mã số thuế: Dãy số có đúng 10 chữ số
- Ngày ký hợp đồng: đúng theo chuẩn dd/mm/yyyy
 
Viết chương trình nhập một nhân viên (không nhập mã) in ra màn hình thông tin của nhân viên đó.

**Input**

Gồm 6 dòng lần lượt ghi các thông tin theo thứ tự đã ghi trong đề bài. Không có mã nhân viên.

**Output**

Ghi ra đầy đủ thông tin nhân viên trên một dòng, các thông tin cách nhau đúng một khoảng trống.

**Ví dụ**

 | **Input** |
|---|
| Nguyen Van Hoa  Nam  22/11/1982  Mo Lao-Ha Dong-Ha Noi  8333123456  31/12/2013 |
| **Output** |
| 00001 Nguyen Van Hoa Nam 22/11/1982 Mo Lao-Ha Dong-Ha Noi 8333123456 31/12/2013 |

### J04008 - CHU VI TAM GIÁC

Khai báo lớp Point (điểm trong không gian hai chiều) có mô tả như sau:

![Alt text](./img/J04008_1.png)

Viết chương trình nhập 3 điểm p1, p2, p3. Hãy tính chu vi tam giác được tạo bởi 3 điểm đó.

**Input**

- Dòng đầu ghi số bộ test, không quá 10
- Mỗi bộ test ghi trên 1 dòng 6 số thực có giá trị tuyệt đối không quá 1000 lần lượt là tọa độ của 3 điểm.
 
**Output**

- Nếu 3 điểm không thể tạo thành tam giác thì in ra INVALID
- Nếu 3 điểm tạo thành 1 tam giác thì in ra chu vi của tam giác đó, làm tròn đến 3 chữ số phần thập phân.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  0 0 0 5 0 199  1 1 1 1 1 1  0 0 0 5 5 0 | INVALID  INVALID  17.071 |

### J04009 - DIỆN TÍCH TAM GIÁC

Khai báo lớp Point (điểm trong không gian hai chiều) có mô tả như sau:

![Alt text](./img/J04009_1.png)

Viết chương trình nhập 3 điểm p1, p2, p3. Hãy tính diện tích tam giác được tạo bởi 3 điểm đó.

*Công thức Heron tính diện tích tam giác khi biết độ dài 3 cạnh là a,b,c:*

*![Alt text](./img/J04009_2.png)*

**Input**

- Dòng đầu ghi số bộ test, không quá 10
- Mỗi bộ test ghi trên 1 dòng 6 số thực có giá trị tuyệt đối không quá 1000 lần lượt là tọa độ của 3 điểm A, B, C.
 
**Output**

- Nếu 3 điểm không thể tạo thành tam giác thì in ra INVALID
- Nếu 3 điểm tạo thành 1 tam giác thì in ra diện tích của tam giác đó, làm tròn đến 2 chữ số phần thập phân.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  0 0 0 5 0 199  1 1 1 1 1 1  0 0 0 5 5 0 | INVALID  INVALID  12.50 |

### J04010 - DIỆN TÍCH HÌNH TRÒN NGOẠI TIẾP TAM GIÁC

Khai báo lớp Point (điểm trong không gian hai chiều) có mô tả như sau:

![Alt text](./img/J04010_1.png)

Nhập 3 điểm p1, p2, p3. Hãy tính diện tích hình tròn ngoại tiếp tam giác tạo bởi 3 điểm trên.

![Alt text](./img/J04010_2.png)

Công thức Heron tính diện tích tam giác với 3 cạnh là a, b, c:

![Alt text](./img/J04010_3.png)

Công thức tính bán kính hình tròn ngoại tiếp:

![Alt text](./img/J04010_4.png)

Khi tính diện tích nên dùng hằng số PI trong lớp Math

**Input**

Dòng đầu ghi số bộ test (không quá 20).

Mỗi bộ test ghi trên 1 dòng 6 số thực lần lượt là tọa độ của 3 điểm A, B, C. Giá trị tọa độ không quá 1000.

**Output**

Nếu 3 điểm không thể tạo thành tam giác, in ra INVALID

Nếu 3 điểm tạo thành tam giác, in ra diện tích hình tròn ngoại tiếp với độ chính xác 3 số phần thập phân.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  0 0 0 5 0 199  1 1 1 1 1 1  0 0 0 5 5 0 | INVALID  INVALID  39.270 |

### J04011 - BỐN ĐIỂM TRÊN MẶT PHẲNG

Cho 4 điểm trong không gian 3 chiều. Nhiệm vụ của bạn là kiểm tra xem chúng có cùng nằm trên một mặt phẳng hay không? Nếu có in ra “YES”, in ra “NO” trong trường hợp ngược lại.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10000).

Mỗi test gồm 4 dòng, lần lượt là tọa độ nguyên x\[i\], y\[i\], z\[i\] của các điểm.

(-1000 ≤ x\[i\], y\[i\], z\[i\] ≤ 1000).

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

 | Input: | Output |
|---|---|
| 3  1 2 0  2 3 0  4 0 0  0 0 0  1 1 1  2 2 2  3 3 3  4 4 4  5 6 7  -8 -9 -10  12 19 0  3 1 5 | YES  YES  NO |

### J04012 - BÀI TOÁN TÍNH CÔNG

Thông tin về nhân viên bao gồm:

- Mã nhân viên (tự động tăng theo thứ tự nhập, tính từ NV01, nếu chỉ có 1 nhân viên thì mã là NV01)
- Họ và tên
- Lương cơ bản mỗi ngày công
- Số ngày công
- Chức vụ
 
Tiền lương được tính bằng lương cơ bản nhân với số ngày công.

Giả sử quy tắc tính tiền thưởng như sau:

- Số ngày công từ 25 trở lên thì thưởng 20% tiền lương
- Số ngày công từ 22 đến dưới 25 thì thưởng 10% tiền lương
- Dưới 22 ngày công thì không có thưởng.
 
Mỗi nhân viên có thể có thêm phụ cấp chức vụ:

- GD: 250000
- PGD: 200000
- TP: 180000
- NV: 150000
 
Hãy nhập thông tin 1 nhân viên và tính toán thu nhập theo quy tắc trên.

**Input**

Gồm 4 dòng lần lượt ghi Họ tên, lương cơ bản, số ngày công và chức vụ.

**Output**

Ghi ra một dòng gồm: mã nhân viên, tên nhân viên, lương tháng, thưởng, phụ cấp và thu nhập. Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| Bui Thi Trang  45000  23  PGD | NV01 Bui Thi Trang 1035000 103500 200000 1338500 |

### J04013 - BÀI TOÁN TUYỂN SINH

Trường Đại học XYZ tuyển sinh theo hình thức xét điểm thi ba môn Toán – Lý – Hóa, trong đó điểm Toán được nhân đôi. Để đơn giản, khu vực tuyển sinh được quy định luôn bởi ba chữ cái đầu tiên trong mã thí sinh. Do rất thích các thí sinh đến từ Khu vực 3 nên trường XYZ tự quy định giá trị điểm ưu tiên Khu vực như trong bảng sau:

![Alt text](./img/J04013_1.png)

Giả sử biết trước điểm chuẩn là 24. Hãy xác định tình trạng của thí sinh.

**Input**

Chỉ bao gồm thông tin của một thí sinh trên 5 dòng lần lượt là:

- Mã thí sinh
- Họ tên
- Điểm toán
- Điểm lý
- Điểm hóa
 
Các giá trị điểm đều đảm bảo trong phạm vi \[0,10\] và có thể có 1 chữ số phần thập phân.

**Output**

Ghi ra các thông tin:

- Mã thí sinh
- Họ tên
- Điểm ưu tiên (có thể có 1 số phần thập phân)
- Tổng điểm – không tính ưu tiên (có thể có 1 số phần thập phân)
- Trạng thái: TRUNG TUYEN hoac TRUOT (sau khi đã tính cả điểm ưu tiên)
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| KV2A002  Hoang Thanh Tuan  5  6  5 | KV2A002 Hoang Thanh Tuan 1 21 TRUOT |
| KV2B123  Ly Thi Thu Ha  8  6.5  7 | KV2B123 Ly Thi Thu Ha 1 29.5 TRUNG TUYEN |

### J04014 - TÍNH TOÁN PHÂN SỐ

Phân số là sự biểu diễn số hữu tỷ dưới dạng tỷ lệ của hai số nguyên, trong đó số ở trên được gọi là tử số, còn số ở dưới được gọi là mẫu số. Cho hai phân số A và B có tử số và mẫu số được nhập từ bàn phím.

Viết chương trình thực hiện hai nhiệm vụ sau:

- Thực hiện phép tính C = (A + B)2 và rút gọn kết quả.
- Thực hiện phép tính D = A x B x C và rút gọn kết quả.
 
**Input:**

Dòng đầu tiên là số bộ test T (T &lt;= 100)

T dòng tiếp theo, mỗi dòng gồm 4 số lần lượt là tử và mẫu số của phân số A và phân số B với -103&lt;= tử số, mẫu số &lt;= 103. Mẫu số đảm bảo khác 0.

**Output:**

Ghi ra kết quả của hai phép tính theo định dạng phân số, cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2    1 2 3 4    2 3 4 5 | 25/16 75/128    484/225 3872/3375 |

### J04015 - TÍNH THU NHẬP GIÁO VIÊN

Trường phổ thông XYZ tính lương giáo viên theo quy tắc sau:

- Mỗi giáo viên có mã ngạch gồm 4 ký tự trong đó
    - 2 ký tự đầu là chức vụ (HT: Giáo viên kiêm nhiệm Hiệu trưởng, HP: Giáo viên kiêm nhiệm Hiệu phó, GV: Giáo viên thường)
    - 2 ký tự số cuối cùng cho biết hệ số bậc lương (không quá 20)
- Lương cơ bản của mỗi giáo viên cũng có thể khác nhau
- Phụ cấp quy định như sau
    - HT: 2.000.000
    - HP: 900.000
    - GV: 500.000
- Thu nhập được tính bằng lương cơ bản nhân với hệ số bậc lương và cộng thêm phụ cấp.
 
Hãy tính lương cho 1 giáo viên theo quy tắc trên.

**Input**

Có 3 dòng lần lượt là mã ngạch, họ tên và lương cơ bản.

**Ouput**

Chỉ có một dòng ghi lần lượt các thông tin: mã ngạch, họ tên, bậc lương, phụ cấp, thu nhập.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| HP04  Tran Quoc Huy  1578000 | HP04 Tran Quoc Huy 4 900000 7212000 |

### J04016 - TÍCH HAI ĐỐI TƯỢNG MA TRẬN

Viết chương trình khai báo lớp Matrix mô tả ma trận các số nguyên.

Sau đó nhập và tính tích hai ma trận A cỡ n\*m và ma trận B cỡ m\*p.

Với 1 &lt; n,m,p &lt; 50. Các giá trị trong ma trận đều nguyên dương và không vượt quá 1000.

**Input**

Dòng đầu ghi 3 số n,m,p

n dòng tiếp theo ghi ma trận A

m dòng tiếp theo ghi ma trận B

**Output**

Ghi ra ma trận tích

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3 4 3  1 2 3 4  4 2 3 1  2 4 1 3  1 1 1  2 2 2  3 3 3  4 4 4 | 30 30 30  21 21 21  25 25 25 |

 **Chú ý: Trong bài này cần viết hàm main đúng theo mô tả.**

### J04017 - TÍCH MA TRẬN VÀ CHUYỂN VỊ CỦA NÓ

Khai báo lớp Matrix mô tả ma trận các số nguyên.

Nhập ma trận A cấp N\*M. Hãy viết chương trình tính tích của A với ma trận chuyển vị của A.

**Input:** Dòng đầu tiên ghi số bộ test. Với mỗi bộ test: Dòng đầu tiên ghi hai số n và m là bậc của ma trân a; n dòng tiếp theo, mỗi dòng ghi m số của một dòng trong ma trận A.

n và m đều nguyên dương và nhỏ hơn 50. Các giá trị trong ma trận không vượt quá 100.

**Output:** Với mỗi bộ test ghi ra ma trận tích tương ứng, mỗi số cách nhau đúng một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  2 2  1 2  3 4 | 5 11  11 25 |

**Chú ý: Trong bài này cần viết hàm main đúng theo mô tả.**

### J04019 - LỚP TRIANGLE - 1

Khai báo lớp Point (điểm trong không gian hai chiều) với hai thuộc tính là tọa độ x và tọa độ y (số thực).

Khai báo lớp Triangle (tam giác) với thuộc tính là 3 điểm. Viết các phương thức phù hợp để tính chu vi tam giác.

**Input**

- Dòng đầu ghi số bộ test, không quá 10
- Mỗi bộ test ghi trên 1 dòng 6 số thực có giá trị tuyệt đối không quá 1000 lần lượt là tọa độ của 3 điểm.
 
**Output**

- Nếu 3 điểm không thể tạo thành tam giác thì in ra INVALID
- Nếu 3 điểm tạo thành 1 tam giác thì in ra chu vi của tam giác đó, làm tròn đến 3 chữ số phần thập phân.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  0 0 0 5 0 199  1 1 1 1 1 1  0 0 0 5 5 0 | INVALID  INVALID  17.071 |

 **Chú ý: cần viết hàm main theo đúng yêu cầu**

### J04020 - LỚP PAIR

Khai báo lớp Pair mô tả các thao tác với cặp số nguyên. Sử dụng lớp Pair để giải quyết bài toán sau (chú ý viết hàm main đúng theo mẫu).

Nhập số tự nhiên N, hãy tìm cặp số nguyên tố đầu tiên có tổng là N.

Nếu không tồn tại cặp số nguyên tố có tổng bằng N, hãy đưa ra -1.

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm là một số N được ghi trên một dòng.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤ N ≤106
 
**Output**:

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output:** |
|---|---|
| 2  4  8 | 2 2  3 5 |

### J04021 - LỚP INTSET

Trong lý thuyết tập hợp, một tập hợp chỉ được phép chứa các giá trị phân biệt và luôn luôn lưu các giá trị theo thứ tự tăng dần.

Khai báo lớp IntSet và viết các phương thức để thực hiện các thao tác trên tập hợp số nguyên. Sử dụng lớp IntSet để in ra tập hợp các số nguyên là hợp của hai tập số trong 2 dãy ban đầu.

Chú ý viết hàm main đúng theo mẫu.

**Input**

Dòng đầu ghi 2 số n và m (1 &lt; n,m &lt;100).

Dòng thứ 2 ghi n số của a\[\]. Dòng thứ 3 ghi m số của b\[\].

Các số đều dương và nhỏ hơn 1000, nhưng có các giá trị trùng nhau và có thể chưa được sắp xếp.

**Output**

Ghi ra hợp của hai tập theo thứ tự tăng dần.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5 6  1 2 3 4 5  3 4 5 6 7 8 | 1 2 3 4 5 6 7 8 |

### J04022 - WORDSET

Trong lập trình cơ bản, một từ được hiểu là một dãy ký tự liên tiếp không chứa khoảng trống, dấu tab hoặc dấu xuống dòng.

  
 Xây dựng lớp WordSet để quản lý tập hợp các từ khác nhau trong một xâu ký tự, sau khi đã chuyển hết về dạng chữ thường. Khi liệt kê thì tập từ thì sẽ luôn theo thứ tự từ điển tăng dần.

Viết chương trình nhập hai dòng ký tự và hiển thị hợp và giao của hai tập từ tương ứng.

**Input**

Chỉ có 2 dòng, mỗi dòng có độ dài không quá 1000 ký tự.

**Output**

Dòng 1 ghi hợp của 2 tập từ theo thứ tự từ điển

Dòng 2 ghi giao của 2 tập từ theo thứ tự từ điển.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| Lap trinh huong doi tuong  Ngon ngu lap trinh C++ | c++ doi huong lap ngon ngu trinh tuong  lap trinh |

### J05063 - TỔNG ĐA THỨC

Cho hai đa thức có bậc không quá 10000 (chỉ viết ra các phần tử có hệ số khác 0). Hãy tính tổng hai đa thức đó.

**Input:** Dòng đầu ghi số bộ test. Mỗi bộ test có hai dòng, mỗi dòng ghi một đa thức theo mẫu như trong ví dụ. Chú ý: Bậc của các hạng tử luôn theo thứ tự giảm dần, trong đa thức chỉ có phép cộng và luôn được viết đầy đủ hệ số + số mũ (kể cả mũ 0).

**Output:** Ghi ra một dòng đa thức tổng tính được (theo mẫu như ví dụ)

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  3\*x^8 + 7\*x^2 + 4\*x^0  11\*x^6 + 9\*x^2 + 2\*x^1 + 3\*x^0 | 3\*x^8 + 11\*x^6 + 16\*x^2 + 2\*x^1 + 7\*x^0 |

 **Chú ý: Trong bài này cần code hàm main đúng theo mẫu.**

### J07009 - LỚP INTSET - 2

Trong lý thuyết tập hợp, một tập hợp chỉ được phép chứa các giá trị phân biệt và luôn luôn lưu các giá trị theo thứ tự tăng dần.

Khai báo lớp IntSet và viết các phương thức để thực hiện các thao tác trên tập hợp số nguyên. Sử dụng lớp IntSet để in ra tập hợp các số nguyên là giao của hai tập số trong 2 dãy ban đầu.

**Input - file văn bản DATA.in**

Dòng đầu ghi 2 số n và m (1 &lt; n,m &lt;100).

Dòng thứ 2 ghi n số của a\[\].

Dòng thứ 3 ghi m số của b\[\].

Các số đều dương và nhỏ hơn 1000.

**Output**

Ghi tập giao của A và B trên một dòng theo thứ tự từ nhỏ đến lớn.

**Ví dụ**

 | **DATA.in** | **Output** |
|---|---|
| 5 6  1 2 3 4 5  3 4 5 6 7 8 | 3 4 5 |

 ***Gợi ý: Xây dựng lớp IntSet có thuộc tính là một TreeSet***

### J07058 - DANH SÁCH MÔN THI

Học viện Hoàng gia tổ chức thi thời kỳ giãn cách theo các hình thức thi linh hoạt, phù hợp với từng môn học.

Thông tin về mỗi môn học gồm:

- Mã môn: xâu ký tự không có khoảng trống, không quá 15 ký tự
- Tên môn: xâu ký tự không có thể có khoảng trống, không quá 100 ký tự
- Hình thức thi: xâu ký tự không có thể có khoảng trống, không quá 100 ký tự
 
Hãy đọc thông tin môn học trong file văn bản MONHOC.in và in danh sách sắp xếp theo mã môn.

**Input – file văn bản MONHOC.in**

Dòng đầu ghi số môn học. Mỗi môn ghi trên 3 dòng lần lượt là mã môn, tên môn, hình thức thi.

**Output**

Ghi ra danh sách đã sắp xếp theo mã môn, thứ tự từ điển.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  MUL1320  Nhap mon da phuong tien  Bai tap lon + Van dap truc tuyen  BAS1203  Giai tich 1  Thi viet + Van dap truc tuyen | BAS1203 Giai tich 1 Thi viet + Van dap truc tuyen  MUL1320 Nhap mon da phuong tien Bai tap lon + Van dap truc tuyen |

## MẢNG ĐỐI TƯỢNG

### J04018 - SỐ PHỨC

Số phức được sử dụng trong nhiều lĩnh vực khoa học, như khoa học kỹ thuật, điện từ học, cơ học lượng tử, toán học ứng dụng.

Số phức là số có thể viết dưới dạng a + b*i*, trong đó a và b là các số nguyên, *i* là đơn vị ảo, với i2 = -1.

Cho hai số phức A = a + b*i*, B = c + d*i*.

Viết chương trình thực hiện thao tác tính toán trên số phức

- C = (A + B) x A
- D = (A + B)2
 
**Input:**

Dòng đầu tiên là số bộ test T (T &lt;= 100)

T dòng tiếp theo mỗi dòng gồm 4 số lần lượt là a, b, c, d, với -102 &lt; a, b, c, d &lt; 102.

**Output:**

Kết quả của hai phép tính theo định dạng

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3    1 2 3 4    2 3 4 5    1 -2 5 -6 | -8 + 14i, -20 + 48i    -12 + 34i, -28 + 96i    -10 - 20i, -28 - 96i |

### J05003 - DANH SÁCH ĐỐI TƯỢNG SINH VIÊN - 1

Viết chương trình khai báo lớp Sinh Viên gồm các thông tin: Mã SV, Họ tên, Ngày sinh, Lớp và Điểm GPA (dạng số thực). Hàm khởi tạo không có tham số, gán các giá trị thuộc tính ở trạng thái mặc định (xâu ký tự rỗng, giá trị số bằng 0).

Đọc thông tin N sinh viên từ bàn phím (không có mã sinh viên) và in ra lần lượt màn hình mỗi dòng 1 sinh viên theo đúng thứ tự ban đầu. Trong đó Mã SV được tự tạo ra theo quy tắc thêm mã **B20DCCN** sau đó là giá trị nguyên tự động tăng tính từ 001 (tối đa là 099). Ngày sinh được chuẩn hóa về dạng dd/mm/yyyy

**Input**

Dòng đầu tiên ghi số sinh viên N (0 &lt; N &lt; 50).

Mỗi sinh viên ghi trên 4 dòng lần lượt là Họ tên, Lớp, Ngày sinh và Điểm GPA.

Trong đó:

- Họ tên không quá 30 chữ cái.
- Lớp theo đúng định dạng thường dùng ở PTIT
- Ngày sinh có đủ 3 phần ngày tháng năm nhưng có thể chưa đúng chuẩn dd/mm/yyyy.
- Điểm GPA đảm bảo trong thang điểm 4 với 2 nhiều nhất 2 số sau dấu phẩy.
 
**Output**

Ghi ra danh sách lần lượt các sinh viên có đầy đủ Mã sinh viên, Họ tên, Lớp, Ngày sinh (đã chuẩn hóa về dạng dd/mm/yyyy), Điểm GPA (với đúng 2 số sau dấu phẩy).

Mỗi sinh viên ghi trên 1 dòng, mỗi thông tin cách nhau 1 khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  Nguyen Van An  D20CQCN01-B  2/12/2002  3.19 | B20DCCN001 Nguyen Van An D20CQCN01-B 02/12/2002 3.19 |

### J05004 - DANH SÁCH ĐỐI TƯỢNG SINH VIÊN - 2

Viết chương trình khai báo lớp Sinh Viên gồm các thông tin: Mã SV, Họ tên, Ngày sinh, Lớp và Điểm GPA (dạng số thực). Hàm khởi tạo không có tham số, gán các giá trị thuộc tính ở trạng thái mặc định (xâu ký tự rỗng, giá trị số bằng 0).

Đọc thông tin N thí sinh từ bàn phím (không có mã sinh viên) và in ra lần lượt màn hình mỗi dòng 1 sinh viên theo đúng thứ tự ban đầu. Trong đó Mã SV được tự tạo ra theo quy tắc thêm mã **B20DCCN** sau đó là giá trị nguyên tự động tăng tính từ 001 (tối đa là 099). Họ tên được xử lý đưa về dạng chuẩn. Ngày sinh được chuẩn hóa về dạng dd/mm/yyyy

**Input**

Dòng đầu tiên ghi số sinh viên N (0 &lt; N &lt; 50).

Mỗi sinh viên ghi trên 4 dòng lần lượt là Họ tên, Lớp, Ngày sinh và Điểm GPA.

Trong đó:

- Họ tên không quá 30 chữ cái.
- Lớp theo đúng định dạng thường dùng ở PTIT
- Ngày sinh có đủ 3 phần ngày tháng năm nhưng có thể chưa đúng chuẩn dd/mm/yyyy.
- Điểm GPA đảm bảo trong thang điểm 4 với 2 nhiều nhất 2 số sau dấu phẩy.
 
**Output**

Ghi ra danh sách lần lượt các sinh viên có đầy đủ Mã sinh viên, Họ tên, Lớp, Ngày sinh (đã chuẩn hóa), điểm GPA (với đúng 2 số sau dấu phẩy).

Mỗi sinh viên ghi trên 1 dòng, mỗi thông tin cách nhau 1 khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  nGuyEn vaN biNH  D20CQCN01-B  2/12/2002  3.1 | B20DCCN001 Nguyen Van Binh D20CQCN01-B 02/12/2002 3.10 |

### J05005 - DANH SÁCH ĐỐI TƯỢNG SINH VIÊN - 3

Viết chương trình khai báo lớp Sinh Viên gồm các thông tin: Mã SV, Họ tên, Ngày sinh, Lớp và Điểm GPA (dạng số thực). Hàm khởi tạo không có tham số, gán các giá trị thuộc tính ở trạng thái mặc định (xâu ký tự rỗng, giá trị số bằng 0).

Đọc thông tin N thí sinh từ bàn phím (không có mã sinh viên) sau đó sắp xếp theo điểm GPA giảm dần và in ra lần lượt màn hình mỗi dòng 1 sinh viên.

Trong đó Mã SV được tự tạo ra theo quy tắc thêm mã **B20DCCN** sau đó là giá trị nguyên tự động tăng tính từ 001 (tối đa là 099). Họ tên được xử lý đưa về dạng chuẩn. Ngày sinh được chuẩn hóa về dạng dd/mm/yyyy

**Input**

Dòng đầu tiên ghi số sinh viên N (0 &lt; N &lt; 50).

Mỗi sinh viên ghi trên 4 dòng lần lượt là Họ tên, Lớp, Ngày sinh và Điểm GPA.

Trong đó:

- Họ tên không quá 30 chữ cái.
- Lớp theo đúng định dạng thường dùng ở PTIT
- Ngày sinh có đủ 3 phần ngày tháng năm nhưng có thể chưa đúng chuẩn dd/mm/yyyy.
- Điểm GPA đảm bảo trong thang điểm 4 với 2 nhiều nhất 2 số sau dấu phẩy.
 
Dữ liệu đảm bảo không có hai sinh viên nào có điểm GPA bằng nhau.

**Output**

Ghi ra danh sách lần lượt các sinh viên có đầy đủ Mã sinh viên, Họ tên, Lớp, Ngày sinh (đã chuẩn hóa), điểm GPA (với đúng 2 số sau dấu phẩy) đã được sắp xếp theo điểm GPA giảm dần.

Mỗi sinh viên ghi trên 1 dòng, mỗi thông tin cách nhau 1 khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  ngUYen Van NaM  D20DCCN01-B  2/12/1994  2.17  Nguyen QuanG hAi  D20DCCN02-B  1/9/1994  3.0 | B20DCCN002 Nguyen Quang Hai D20DCCN02-B 01/09/1994 3.00  B20DCCN001 Nguyen Van Nam D20DCCN01-B 02/12/1994 2.17 |

### J05006 - DANH SÁCH ĐỐI TƯỢNG NHÂN VIÊN

Một nhân viên làm việc trong công ty được lưu lại các thông tin sau:

- Mã nhân viên: được gán tự động tăng, bắt đầu từ 00001
- Họ tên: Xâu ký tự không quá 40 chữ cái.
- Giới tính: Nam hoặc Nu
- Ngày sinh: đúng theo chuẩn dd/mm/yyyy
- Địa chỉ: Xâu ký tự không quá 100 chữ cái
- Mã số thuế: Dãy số có đúng 10 chữ số
- Ngày ký hợp đồng: đúng theo chuẩn dd/mm/yyyy
 
Viết chương trình nhập danh sách nhân viên (không nhập mã) và in ra màn hình danh sách vừa nhập.

**Input**

Dòng đầu ghi số N là số nhân viên (không quá 40). Mối nhân viên ghi trên 6 dòng lần lượt ghi các thông tin theo thứ tự đã ghi trong đề bài. Không có mã nhân viên.

**Output**

Ghi ra danh sách đầy đủ nhân viên, mỗi nhân viên trên một dòng, các thông tin cách nhau đúng một khoảng trống.

**Ví dụ**

 | **Input** |
|---|
| 3  Nguyen Van A  Nam  22/10/1982  Mo Lao-Ha Dong-Ha Noi  8333012345  31/12/2013  Ly Thi B  Nu  15/10/1988  Mo Lao-Ha Dong-Ha Noi  8333012346  22/08/2011  Hoang Thi C  Nu  04/02/1981  Mo Lao-Ha Dong-Ha Noi  8333012347  22/08/2011 |
| **Output** |
| 00001 Nguyen Van A Nam 22/10/1982 Mo Lao-Ha Dong-Ha Noi 8333012345 31/12/2013  00002 Ly Thi B Nu 15/10/1988 Mo Lao-Ha Dong-Ha Noi 8333012346 22/08/2011  00003 Hoang Thi C Nu 04/02/1981 Mo Lao-Ha Dong-Ha Noi 8333012347 22/08/2011 |

### J05007 - SẮP XẾP DANH SÁCH ĐỐI TƯỢNG NHÂN VIÊN

Một nhân viên làm việc trong công ty được lưu lại các thông tin sau:

- Mã nhân viên: được gán tự động tăng, bắt đầu từ 00001
- Họ tên: Xâu ký tự không quá 40 chữ cái.
- Giới tính: Nam hoặc Nu
- Ngày sinh: đúng theo chuẩn dd/mm/yyyy
- Địa chỉ: Xâu ký tự không quá 100 chữ cái
- Mã số thuế: Dãy số có đúng 10 chữ số
- Ngày ký hợp đồng: đúng theo chuẩn dd/mm/yyyy
 
Viết chương trình nhập danh sách nhân viên (không nhập mã) sau đó sắp xếp theo thứ tự ngày sinh từ già nhất đến trẻ nhất và in ra màn hình danh sách đối tượng nhân viên đã sắp xếp.

**Input**

Dòng đầu ghi số N là số nhân viên (không quá 40). Mỗi nhân viên ghi trên 6 dòng lần lượt ghi các thông tin theo thứ tự đã ghi trong đề bài. Không có mã nhân viên.

**Output**

Ghi ra danh sách đầy đủ nhân viên đã sắp xếp, mỗi nhân viên trên một dòng, các thông tin cách nhau đúng một khoảng trống.

**Ví dụ**

 | **Input** |
|---|
| 3  Nguyen Van A  Nam  22/10/1982  Mo Lao-Ha Dong-Ha Noi  8333012345  31/12/2013  Ly Thi B  Nu  15/10/1988  Mo Lao-Ha Dong-Ha Noi  8333012346  22/08/2011  Hoang Thi C  Nu  04/02/1981  Mo Lao-Ha Dong-Ha Noi  8333012347  22/08/2011 |
| **Output** |
| 00003 Hoang Thi C Nu 04/02/1981 Mo Lao-Ha Dong-Ha Noi 8333012347 22/08/2011  00001 Nguyen Van A Nam 22/10/1982 Mo Lao-Ha Dong-Ha Noi 8333012345 31/12/2013  00002 Ly Thi B Nu 15/10/1988 Mo Lao-Ha Dong-Ha Noi 8333012346 22/08/2011 |

### J05008 - DIỆN TÍCH ĐA GIÁC

Khai báo lớp Point (điểm trong không gian hai chiều) có mô tả như sau:

![Alt text](./img/J05008_1.png)

Hãy sử dụng lớp Point để giải quyết bài toán sau.

Cho một đa giác lồi có N đỉnh trên mặt phẳng Oxy.

Nhiệm vụ của bạn là hãy tính diện tích đa giác này.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 100).

Mỗi test bắt đầu bởi số nguyên N (N ≤ 1000).

N dòng tiếp theo, mỗi dòng gồm 2 số nguyên x\[i\], y\[i\] (-1000 ≤ x\[i\], y\[i\] ≤ 1000) là tọa độ của điểm thứ i. Các điểm được liệt kê theo thứ tự ngược chiều kim đồng hồ.

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

 | **Input:** | **Output** |
|---|---|
| 2  3  0 0  1 0  0 1  4  0 0  2 0  2 2  0 2 | 0.500  4.000 |

### J05009 - TÌM THỦ KHOA CỦA KỲ THI

Cho danh sách thí sinh gồm các thông tin: Mã thí sinh: là một số nguyên, tự động tăng, tính từ 1; Tên thí sinh, ngày sinh, điểm môn 1, điểm môn 2, điểm môn 3. Hãy tìm thủ khoa trong danh sách đó. Nếu có nhiều thí sinh có điểm bằng nhau và đều cao nhất thì in ra tất cả thí sinh đó theo mã tăng dần.

**Dữ liệu vào**

Dòng đầu chứa số thí sinh. Mỗi thí sinh viết trên 3 dòng: Dòng 1: Tên thí sinh, Dòng 2: Ngày sinh, Dòng 3,4,5: 3 điểm thi tương ứng. Các điểm thi đều đảm bảo hợp lệ (từ 0 đến 10).

**Kết quả:** In ra các thủ khoa của kỳ thi, mỗi thí sinh 1 dòng, gồm mã, tên, ngày sinh và tổng điểm.

**Ví dụ:**

 | Input | Output |
|---|---|
| 3    Nguyen Van A    12/12/1994    3.5    7.0    5.5    Nguyen Van B    1/9/1994    7.5    9.5    9.5    Nguyen Van C    6/7/1994    8.5    9.5    8.5 | 2 Nguyen Van B 1/9/1994 26.5    3 Nguyen Van C 6/7/1994 26.5 |

### J05010 - SẮP XẾP DANH SÁCH MẶT HÀNG

Hãy sắp xếp danh sách các mặt hàng theo lợi nhuận giảm dần. Mỗi mặt hàng gồm các thông tin: Mã mặt hàng (là một số nguyên, tự động tăng, tính từ 1); Tên mặt hàng, nhóm hàng: là các xâu ký tự; Giá mua, giá bán: là các số thực (không quá 9 chữ số)

**Dữ liệu vào**

Dòng đầu chứa số mặt hàng. Mỗi mặt hàng viết trên 4 dòng: Dòng 1: Tên mặt hàng. Dòng 2: Nhóm hàng. Dòng 3: Giá mua. Dòng 4: Giá bán

**Kết quả:** Ghi ra danh sách mặt hàng đã sắp xếp theo lợi nhuận giảm dần (lợi nhuận tính bằng giá bán trừ đi giá mua). Mỗi mặt hàng viết trên một dòng gồm: mã, tên, nhóm hàng và lợi nhuận (với 2 chữ số sau dấu phẩy). Các thông tin cách nhau đúng 1 khoảng trống.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  May tinh SONY VAIO  Dien tu  16400  17699  Tu lanh Side by Side  Dien lanh  18300  25999  Banh Chocopie  Tieu dung  27.5    37 | 2 Tu lanh Side by Side Dien lanh 7699.00  1 May tinh SONY VAIO Dien tu 1299.00  3 Banh Chocopie Tieu dung 9.50 |

### J05011 - TÍNH GIỜ

Quán Game mùa này vắng khách nên chủ quán quyết định tính tiền chi tiết đến từng phút. Dựa trên dữ liệu giờ vào và giờ ra, hãy tính thời gian chơi game của các Game thủ nhé.

**Input**

Dòng đầu của dữ liệu vào ghi số lượng game thủ trong ngày (không quá 20).

Thông tin về một game thủ đến chơi game được ghi lại trên 4 dòng lần lượt là:

- Mã người chơi (xâu ký tự độ dài không quá 10, không có khoảng trống)
- Tên người chơi (xâu ký tự độ dài không quá 100, có thể có khoảng trống).
- Giờ vào (định dạng hh:mm)
- Giờ ra (định dạng hh:mm)
 
Dữ liệu vào đảm bảo không có cặp game thủ nào có thời gian bằng nhau.

**Ouput**

Ghi ra danh sách game thủ đã được sắp xếp theo thời gian chơi game giảm dần.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  01T  Nguyen Van An  09:00  10:30  06T  Hoang Van Nam  15:30  18:00  02I  Tran Hoa Binh  09:05  10:00 | 06T Hoang Van Nam 2 gio 30 phut  01T Nguyen Van An 1 gio 30 phut  02I Tran Hoa Binh 0 gio 55 phut |

### J05012 - TÍNH TIỀN

Cửa hàng điện máy – điện lạnh cần lập hóa đơn tính tiền cho khách hàng. Mỗi mặt hàng sẽ có đơn giá và một số tiền được gọi là chiết khấu trên tổng hóa đơn. Số tiền phải thanh toán sẽ bằng đơn giá \* số lượng sau đó trừ đi tiền chiết khấu.

Hãy tính tiền cho từng hóa đơn và sắp xếp theo số tiền giảm dần.

**Input**

Dòng đầu ghi số lượng hóa đơn. Không quá 20.

Mỗi thông tin hóa đơn gồm 5 dòng:

- Mã mặt hàng (xâu ký tự độ dài không quá 10, không có khoảng trống)
- Tên mặt hàng (xâu ký tự độ dài không quá 100, có thể có khoảng trống)
- Số lượng mua (không quá 50)
- Đơn giá (số nguyên dương có thể đến 10 chữ số)
- Tiền chiết khấu của hóa đơn (có thể đến 9 chữ số).
 
**Output**

Ghi ra danh sách hóa đơn đã sắp xếp, trong đó mỗi dòng gồm đầy đủ 6 thông tin: mã mặt hàng, tên mặt hàng, số lượng mua, đơn giá, chiết khấu và tổng tiền. Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  ML01  May lanh SANYO  12  4000000  2400000  ML02  May lanh HITACHI  4  2550000000  0  ML03  May lanh NATIONAL  5  3000000  150000 | ML02 May lanh HITACHI 4 2550000000 0 10200000000  ML01 May lanh SANYO 12 4000000 2400000 45600000  ML03 May lanh NATIONAL 5 3000000 150000 14850000 |

### J05013 - TUYỂN DỤNG

Doanh nghiệp X cần tuyển một số nhân viên mới. Bài thi tuyển có hai phần: lý thuyết và thực hành. Sau khi tính điểm trung bình, các thí sinh sẽ được xếp thành 4 loại:

- Nếu điểm dưới 5 -&gt; TRUOT
- Nếu điểm lớn hơn 5 nhưng nhỏ hơn 8 -&gt; CAN NHAC
- Nếu điểm từ 8 đến 9.5 -&gt; DAT
- Nếu điểm lớn hơn 9.5 -&gt; XUAT SAC
 
Điểm các bài thi lý thuyết và thực hành đều là số thực trong phạm vi từ 0 đến 10. Tuy nhiên, khi nhập điểm các bài thi, cán bộ tuyển dụng có thể quên mất dấu . phân cách phần nguyên và phần thập phân. Do đó nếu điểm ghi là 78 thì cần được hiểu là 7.8. Tuy nhiên, điểm 10 thì vẫn ghi là 10 (không có giá trị điểm nào bằng 1.0).

Hãy sắp xếp danh sách thí sinh đã được xếp loại theo điểm trung bình giảm dần.

**Input**

Dòng đầu ghi số thí sinh. Mỗi thí sinh ghi trên 3 dòng lần lượt là:

- Họ và tên (xâu ký tự độ dài không quá 100)
- Điểm lý thuyết
- Điểm thực hành
 
Mã thí sinh cần được tự động gán theo mẫu TS + số thứ tự (tính từ 01).

**Output**

Ghi ra danh sách thí sinh đã sắp xếp, mỗi thí sinh gồm 4 thông tin: mã thí sinh, họ tên, điểm trung bình (với 2 số phần thập phân) và xếp loại. Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Nguyen Thai Binh  45  75  Le Cong Hoa  4  4.5  Phan Van Duc  56  56 | TS01 Nguyen Thai Binh 6.00 CAN NHAC  TS03 Phan Van Duc 5.60 CAN NHAC  TS02 Le Cong Hoa 4.25 TRUOT |

### J05014 - TUYỂN GIÁO VIÊN

Trường THPT ACB tuyển giáo viên mới cho ba môn Toán, Lý, Hóa. Theo yêu cầu mới, bài thi tuyển gồm 2 nội dung: Tin học và Chuyên môn. Điểm thi Tin học sẽ được nhân đôi khi tính tổng điểm.

Mỗi GV có thể có điểm ưu tiên được xét theo mã như trong bảng sau:

![Alt text](./img/J05014_1.png)

Mã xét tuyển gồm 2 thành phần. Chữ cái đầu tiên ứng với môn học: A là Toán, B là Lý và C là Hóa; tiếp theo là 1 chữ số thể hiện mã ưu tiên.

Tổng điểm sau khi cộng điểm ưu tiên nếu từ 18 trở lên sẽ được xét TRÚNG TUYỂN, nhỏ hơn sẽ bị LOẠI.

Viết chương trình nhập danh sách điểm thi và sắp xếp GV theo thứ tự tổng điểm giảm dần. Mã GV dự thi được tự động gán theo thứ tự bắt đầu từ 01.

**Input**

Dòng đầu thi số giáo viên đăng ký thi tuyển (không quá 20).

Mỗi GV được viết trên 4 dòng gồm:

- Tên GV (xâu ký tự độ dài không quá 50)
- Mã xét tuyển
- Điểm tin học (số thực trong phạm vi 0 đến 10)
- Điểm chuyên môn (số thực trong phạm vi 0 đến 10)
 
**Output**

Ghi ra danh sách đã sắp xếp. Thông tin mỗi GV gồm: Mã GV, Tên, Môn học, Tổng điểm (1 chữ số phần thập phân), Kết quả. Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Le Van Binh  A1  7.0  3.0  Tran Van Toan  B3  4.0  7.0  Hoang Thi Tam  C2  7.0  6.0 | GV03 Hoang Thi Tam HOA 21.5 TRUNG TUYEN  GV01 Le Van Binh TOAN 19.0 TRUNG TUYEN  GV02 Tran Van Toan LY 16.0 LOAI |

### J05015 - ĐUA XE ĐẠP

Cuộc đua xe đạp bắt đầu từ **6h00** với độ dài quãng đường đua là **120 Km**. Các cua-rơ sẽ được ghi nhận thành tích dựa trên thời điểm đến đích. Hãy xếp hạng theo thứ tự thành tích giảm dần.

**Input**

Dòng đầu ghi số cua-rơ tham gia cuộc đua.

Mỗi cua-rơ ghi trên 3 dòng:

- Họ tên (xâu ký tự độ dài không quá 50)
- Đơn vị (xâu ký tự độ dài không quá 20)
- Thời điểm đến đích theo định dạng h:mm
 
**Output**

Ghi ra danh sách đã sắp xêp theo thành tích, tốt hơn xếp trước, kém hơn xếp sau.

Thông tin mỗi cua-rơ bao gồm:

- Mã (là chữ cái đầu tiên của các từ trong tên đơn vị ghép với chữ cái đầu tiên các từ trong họ tên – xem ví dụ để hiểu rõ hơn)
- Họ tên
- Đơn vị
- Vận tốc trung bình (đã làm tròn ra giá trị nguyên)
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Tran Vu Minh  Ha Noi  8:30  Vu Ngoc Hoang  Hoa Binh  8:20  Pham Dinh Tan  An Giang  8:45 | HBVNH Vu Ngoc Hoang Hoa Binh 51 Km/h  HNTVM Tran Vu Minh Ha Noi 48 Km/h  AGPDT Pham Dinh Tan An Giang 44 Km/h |

### J05016 - HÓA ĐƠN KHÁCH SẠN

Khách sạn XYZ có đơn giá (theo ngày) được quy định khác nhau theo từng tầng. Khách hàng đến thuê phòng sẽ được tính tổng số tiền ở theo đơn giá cộng thêm chi phí dịch vụ phát sinh nếu có.

![Alt text](./img/J05016_1.png)

Hãy giúp khách sạn tính tiền phải trả cho từng khách hàng và sắp xếp theo thứ tự tổng tiền giảm dần.

**Input**

Dòng đầu ghi số khách hàng (không quá 20)

Mỗi khách hàng ghi trên 4 dòng gồm:

- Tên khách hàng (xâu ký tự độ dài không quá 100)
- Số phòng
- Ngày nhận phòng (định dạng dd/mm/yyyy)
- Ngày trả phòng (định dạng dd/mm/yyyy)
- Tiền dịch vụ phát sinh (số nguyên dương nhỏ hơn 100)
 
**Output**

Ghi ra danh sách đã được sắp xếp theo tổng tiền giảm dần bao gồm lần lượt các thông tin:

- Mã khách hàng (tự động tăng theo thứ tự nhập, tính từ KH01)
- Tên khách hàng
- Số phòng
- Số ngày ở
- Thành tiền
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Huynh Van Thanh  103  05/06/2010  05/06/2010  15  Le Duc Cong  106  08/03/2010  01/05/2010  220  Tran Thi Bich Tuyen  207  10/04/2010  21/04/2010  96 | KH02 Le Duc Cong 106 55 1595  KH03 Tran Thi Bich Tuyen 207 12 504  KH01 Huynh Van Thanh 103 1 40 |

### J05017 - HÓA ĐƠN TIỀN NƯỚC

Tiền nước hàng tháng của thành phố ABC được tính theo đơn giá trong bảng sau:

![Alt text](./img/J05017_1.png)

Trong đó, phụ phí được hiểu là số tiền tính thêm (theo phần trăm) trên tổng số tiền nước tiêu thụ.

Cho danh sách khách hàng và chỉ số đồng hộ. Hãy sắp xếp danh sách hóa đơn theo tổng số tiền giảm dần.

**Input**

Dòng đầu ghi số khách hàng (không quá 20).

Mỗi khách hàng viết trên 3 dòng gồm:

- Tên khách hàng (xâu ký tự độ dài không quá 50)
- Chỉ số cũ
- Chỉ số mới
 
Trong đó chỉ số mới lớn hơn hoặc bằng chỉ số cũ, cả hai đều không quá 4 chữ số.

**Output**

Ghi ra danh sách khách hàng đã sắp xếp theo tổng tiền giảm dần gồm các thông tin

- Mã khách hàng (tự động gán tăng dần theo thứ tự nhập, bắt đầu từ KH01)
- Tên khách hàng
- Tổng số tiền (được làm tròn ở dạng số nguyên)
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Le Thi Thanh  468  500  Le Duc Cong  160  230  Ha Hue Anh  410  612 | KH03 Ha Hue Anh 34545  KH02 Le Duc Cong 8240  KH01 Le Thi Thanh 3264 |

### J05018 - BẢNG ĐIỂM HỌC SINH

Trường THCS XYZ lập bảng điểm tổng kết cho học sinh. Có 10 môn học lần lượt gồm: Toán, Tiếng Việt, Ngoại ngữ, Vật lý, Hóa học, Sinh học, Lịch Sử, Địa, Giáo dục công dân và môn Công nghệ. Trong đó môn Toán và Tiếng Việt tính hệ số 2, các môn còn lại hệ số 1.

Học sinh được xếp hạng theo điểm trung bình:

- Từ 9 trở lên: loại XUAT SAC
- Từ 8 đến 8.9: loại GIOI
- Từ 7 đến 7.9: loại KHA
- Từ 5 đến 6.9: loại TB
- Dưới 5: loai YEU
 
Hãy lập bảng điểm tổng kết và sắp xếp theo điểm trung bình giảm dần.

**Input**

Dòng đầu ghi số học sinh (không quá 50).

Thông tin về mỗi học sinh có hai dòng: dòng đầu là họ tên (độ dài không quá 50), dòng thứ 2 gồm 10 số thực trong đoạn \[0..10\] lần lượt là điểm 10 môn theo đúng thứ tự đã mô tả.

**Output**

Danh sách đã sắp xếp được ghi ra bao gồm các thông tin:

- Mã học sinh (tự động gán tăng dần theo thứ tự nhập, bắt đầu là HS01)
- Họ và tên
- Điểm trung bình (với 1 chữ số phần thập phân)
- Xếp loại
 
Trong trường hợp điểm trung bình bằng nhau thì học sinh nào có mã học sinh nhỏ hơn sẽ xếp trên.

**Ví dụ**

 | **Input** |
|---|
| 3  Luu Thuy Nhi  9.3 9.0 7.1 6.5 6.2 6.0 8.2 6.7 4.8 5.5  Le Van Tam  8.0 8.0 5.5 9.0 6.8 9.0 7.2 8.3 7.2 6.8  Nguyen Thai Binh  9.0 6.4 6.0 7.5 6.7 5.5 5.0 6.0 6.0 6.0 |
| **Output** |
| HS02 Le Van Tam 7.7 KHA  HS01 Luu Thuy Nhi 7.3 KHA  HS03 Nguyen Thai Binh 6.6 TB |

### J05019 - LƯỢNG MƯA TRUNG BÌNH

Trong một ngày mưa nhiều, các trạm đo mưa hoạt động hết công suất. Tại mỗi trạm đo, các cơn mưa được ghi nhận thời điểm bắt đầu, thời điểm kết thúc và lượng mưa đo được. Một trạm mưa có thể có nhiều lần mưa trong ngày.

Hãy tính lượng mưa trung bình trong 1 giờ (60 phút) của từng trạm theo đúng thứ tự trong danh sách ban đầu. Chú ý để tính lượng mưa trung bình thì cần tính tất các lần đo mưa tại trạm đó.

**Input**

Dòng đầu ghi số lượt đo lượng mưa.

Thông tin về một lần đo lượng mưa gồm 4 dòng:

- Tên trạm
- Thời điểm bắt đầu mưa (hh:mm)
- Thời điểm kết thúc mưa (hh:mm)
- Lượng mưa đo được
 
Số trạm đo khác nhau nhỏ hơn 10.

**Output**

Ghi ra danh sách các trạm khác nhau trong danh sách đo mưa và lượng mưa trung bình của từng trạm.

Thông tin trên mỗi dòng lần lượt gồm:

- Mã trạm đo (tính từ T01). Chú ý: nếu cùng tên trong danh sách đo thì cũng sẽ cùng mà trạm.
- Tên trạm đo mưa
- Lượng mưa trung bình trong 1 giờ tại mỗi trạm (tính chính xác đến 2 số phần thập phân).
 
Các thông tin ghi cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 10  Dong Anh  07:30  08:00  60  Cau Giay  07:45  08:12  50  Soc Son  08:00  09:15  78  Dong Anh  18:50  20:00  88  Cau Giay  19:01  20:00  77  Soc Son  19:06  20:21  66  Dong Anh  21:00  21:40  49  Cau Giay  21:50  22:20  68  Dong Anh  22:15  23:45  30  Cau Giay  22:50  23:45  35 | T01 Dong Anh 59.22  T02 Cau Giay 80.70  T03 Soc Son 57.60 |

### J05020 - SẮP XẾP SINH VIÊN THEO LỚP

Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 15)
 
Hãy nhập danh sách sinh viên và sắp xếp theo lớp tăng dần (thứ tự từ điển)

**Input**

Dòng đầu ghi số sinh viên.

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

Có không quá 1000 sinh viên trong danh sách.

**Output**

Ghi ra danh sách sinh viên đã sắp xếp theo lớp. Mỗi sinh viên trên một dòng, các thông tin cách nhau một khoảng trống.

Nếu 2 sinh viên có cùng lớp thì sắp xếp theo mã tăng dần (thứ tự từ điển)

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  B16DCCN011  Nguyen Trong Duc Anh  D16CNPM1  sv1@stu.ptit.edu.vn  B15DCCN215  To Ngoc Hieu  D15CNPM3  sv2@stu.ptit.edu.vn  B15DCKT150  Nguyen Ngoc Son  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  Nguyen Trong Tung  D15CQKT03-B  sv4@stu.ptit.edu.vn | B15DCCN215 To Ngoc Hieu D15CNPM3 sv2@stu.ptit.edu.vn  B15DCKT150 Nguyen Ngoc Son D15CQKT02-B sv3@stu.ptit.edu.vn  B15DCKT199 Nguyen Trong Tung D15CQKT03-B sv4@stu.ptit.edu.vn  B16DCCN011 Nguyen Trong Duc Anh D16CNPM1 sv1@stu.ptit.edu.vn |

### J05021 - SẮP XẾP THEO MÃ SINH VIÊN

Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 15)
 
Hãy nhập danh sách sinh viên và sắp xếp theo mã sinh viên tăng dần (thứ tự từ điển)

**Input**

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

Không cho biết số sinh viên nhưng dữ liệu đảm bảo là chẵn lần 4 dòng.

Có không quá 1000 sinh viên trong danh sách.

**Output**

Ghi ra danh sách sinh viên đã sắp xếp theo mã. Mỗi sinh viên trên một dòng, các thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| B16DCCN011  Nguyen Trong Duc Anh  D16CNPM1  sv1@stu.ptit.edu.vn  B15DCCN215  To Ngoc Hieu  D15CNPM3  sv2@stu.ptit.edu.vn  B15DCKT150  Nguyen Ngoc Son  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  Nguyen Trong Tung  D15CQKT03-B  sv4@stu.ptit.edu.vn | B15DCCN215 To Ngoc Hieu D15CNPM3 sv2@stu.ptit.edu.vn  B15DCKT150 Nguyen Ngoc Son D15CQKT02-B sv3@stu.ptit.edu.vn  B15DCKT199 Nguyen Trong Tung D15CQKT03-B sv4@stu.ptit.edu.vn  B16DCCN011 Nguyen Trong Duc Anh D16CNPM1 sv1@stu.ptit.edu.vn |

### J05022 - LIỆT KÊ SINH VIÊN THEO LỚP

Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 15)
 
Hãy nhập danh sách sinh viên và liệt kê sinh viên theo lớp

**Input**

Dòng đầu ghi số sinh viên (không quá 1000)

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

Sau đó sẽ có giá trị số Q là số truy vấn

Tiếp theo là Q dòng, mỗi dòng ghi một lớp

**Output**

Với mỗi truy vấn, liệt kê danh sách sinh viên của lớp đó theo mẫu như trong ví dụ. Mỗi sinh viên ghi trên một dòng, các thông tin cách nhau một khoảng trống. Thứ tự sinh viên vẫn giữ nguyên như thứ tự ban đầu.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  B16DCCN011  Nguyen Trong Duc Anh  D16CNPM1  sv1@stu.ptit.edu.vn  B15DCCN215  To Ngoc Hieu  D15CNPM3  sv2@stu.ptit.edu.vn  B15DCKT150  Nguyen Ngoc Son  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  Nguyen Trong Tung  D15CQKT02-B  sv4@stu.ptit.edu.vn  1  D15CQKT02-B | DANH SACH SINH VIEN LOP D15CQKT02-B:  B15DCKT150 Nguyen Ngoc Son D15CQKT02-B sv3@stu.ptit.edu.vn  B15DCKT199 Nguyen Trong Tung D15CQKT02-B sv4@stu.ptit.edu.vn |

### J05023 - LIỆT KÊ SINH VIÊN THEO KHÓA

Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 15)
 
Hãy nhập danh sách sinh viên và liệt kê sinh viên theo khóa học. Chú ý: dữ liệu khóa học thể hiện qua hai chữ số thứ 2 và thứ 3 trong mã sinh viên.

**Input**

Dòng đầu ghi số sinh viên (không quá 1000)

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

Sau đó sẽ có giá trị số Q là số truy vấn

Tiếp theo là Q dòng, mỗi dòng ghi năm bắt đầu khóa học theo định dạng yyyy

**Output**

Với mỗi truy vấn, liệt kê danh sách sinh viên của khóa đó theo mẫu như trong ví dụ. Mỗi sinh viên ghi trên một dòng, các thông tin cách nhau một khoảng trống. Thứ tự sinh viên vẫn giữ nguyên như thứ tự ban đầu.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  B16DCCN011  Nguyen Trong Duc Anh  D16CNPM1  sv1@stu.ptit.edu.vn  B15DCCN215  To Ngoc Hieu  D15CNPM3  sv2@stu.ptit.edu.vn  B15DCKT150  Nguyen Ngoc Son  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  Nguyen Trong Tung  D15CQKT02-B  sv4@stu.ptit.edu.vn  1  2015 | DANH SACH SINH VIEN KHOA 2015:  B15DCCN215 To Ngoc Hieu D15CNPM3 sv2@stu.ptit.edu.vn  B15DCKT150 Nguyen Ngoc Son D15CQKT02-B sv3@stu.ptit.edu.vn  B15DCKT199 Nguyen Trong Tung D15CQKT02-B sv4@stu.ptit.edu.vn |

### J05024 - LIỆT KÊ SINH VIÊN THEO NGÀNH

Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 15)
 
Hãy nhập danh sách sinh viên và liệt kê sinh viên theo ngành.

**Input**

Dòng đầu ghi số sinh viên (không quá 1000)

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

Sau đó sẽ có giá trị số Q là số truy vấn

Tiếp theo là Q dòng, mỗi dòng ghi ngành đào tạo. Chỉ có 3 ngành đào tạo trong danh sách sau (trong Input sẽ không có dấu):

- **Kế toán** – mã sinh viên có cụm ký tự DCKT
- **Công nghệ thông tin** – mã sinh viên có cụm DCCN – trừ đi các sinh viên lớp bắt đầu bằng chữ E
- **An toàn thông tin** – mã sinh viên có cụm DCAT – trừ các sinh viên lớp bắt đầu bằng chữ E
- **Viễn thông** – mã sinh viên có cụm DCVT
- **Điện tử** - mã sinh viên có cụm DCDT
 
**Output**

Với mỗi truy vấn, liệt kê danh sách sinh viên của ngành đó theo mẫu như trong ví dụ. Mỗi sinh viên ghi trên một dòng, các thông tin cách nhau một khoảng trống. Thứ tự sinh viên vẫn giữ nguyên như thứ tự ban đầu.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  B16DCCN011  Nguyen Trong Duc Anh  D16CNPM1  sv1@stu.ptit.edu.vn  B15DCCN215  To Ngoc Hieu  D15CNPM3  sv2@stu.ptit.edu.vn  B15DCKT150  Nguyen Ngoc Son  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  Nguyen Trong Tung  D15CQKT02-B  sv4@stu.ptit.edu.vn  1  Ke toan | DANH SACH SINH VIEN NGANH KE TOAN:  B15DCKT150 Nguyen Ngoc Son D15CQKT02-B sv3@stu.ptit.edu.vn  B15DCKT199 Nguyen Trong Tung D15CQKT02-B sv4@stu.ptit.edu.vn |

### J05025 - SẮP XẾP DANH SÁCH GIẢNG VIÊN

Danh sách giảng viên Khoa CNTT cần được sắp xếp lại theo tên. Thông tin về giảng viên ban đầu chỉ có họ tên và Bộ môn. Mã giảng viên tự động tăng, tính từ GV01.

Cần sắp xếp lại theo tên (tức là từ cuối cùng trong xâu họ tên). Các giảng viên có cùng tên thì được sắp xếp theo mã giảng viên.

**Input**

Dòng đầu ghi số giảng viên (không quá 50).

Mỗi giảng viên ghi trên 2 dòng gồm họ tên (không quá 50 ký tự) và Bộ môn (không quá 30 ký tự).

**Output**

Danh sách đã sắp xếp trong đó mỗi giảng viên ghi trên một dòng. Mã được tự động điền theo thứ tự nhập, bộ môn được viết tắt theo các chữ cái đầu của từng từ và ở dạng in hoa.

**Ví dụ**

 | **Input** | **Ouput** |
|---|---|
| 3  Nguyen Manh Son  Cong nghe phan mem  Vu Hoai Nam  Khoa hoc may tinh  Dang Minh Tuan  An toan thong tin | GV02 Vu Hoai Nam KHMT  GV01 Nguyen Manh Son CNPM  GV03 Dang Minh Tuan ATTT |

### J05026 - DANH SÁCH GIẢNG VIÊN THEO BỘ MÔN

Thông tin về giảng viên Khoa CNTT ban đầu chỉ có họ tên và Bộ môn. Mã giảng viên sẽ tự động điền tăng dần, tính từ GV01.

Hãy liệt kê danh sách giảng viên của Bộ môn được yêu cầu.

**Input**

Dòng đầu ghi số giảng viên.

Mỗi giảng viên ghi trên 2 dòng gồm họ tên (không quá 50 ký tự) và Bộ môn (không quá 30 ký tự).

Tiếp theo là một dòng ghi số Q là số truy vấn.

Mỗi truy vấn là tên một bộ môn trên một dòng.

**Output**

Danh sách các giảng viên của bộ môn theo từng truy vấn, trong đó mỗi giảng viên ghi trên một dòng. Mã được tự động điền theo thứ tự nhập, bộ môn được viết tắt theo các chữ cái đầu của từng từ và ở dạng in hoa.

Thứ tự giảng viên của mỗi bộ môn được liệt kê theo đúng thứ tự ban đầu.

**Ví dụ**

 | **Input** | **Ouput** |
|---|---|
| 3  Nguyen Manh Son  Cong nghe phan mem  Vu Hoai Nam  Khoa hoc may tinh  Dang Minh Tuan  An toan thong tin  1  Cong nghe phan mem | DANH SACH GIANG VIEN BO MON CNPM:  GV01 Nguyen Manh Son CNPM |

### J05027 - TÌM KIẾM GIẢNG VIÊN

Thông tin về giảng viên Khoa CNTT ban đầu chỉ có họ tên và Bộ môn. Mã giảng viên sẽ tự động điền tăng dần, tính từ GV01.

Hãy tìm kiếm giảng viên theo tên *(yêu cầu tìm gần đúng – tức là trong tên giảng viên xuất hiện từ hoặc cụm từ khóa, không phân biệt chữ hoa chữ thường).*

**Input**

Dòng đầu ghi số giảng viên.

Mỗi giảng viên ghi trên 2 dòng gồm họ tên (không quá 50 ký tự) và Bộ môn (không quá 30 ký tự).

Tiếp theo là một dòng ghi số Q là số truy vấn.

Mỗi truy vấn là một từ khóa cần tìm.

**Output**

Danh sách các giảng viên tìm được theo từ khóa, trong đó mỗi giảng viên ghi trên một dòng. Mã được tự động điền theo thứ tự nhập, bộ môn được viết tắt theo các chữ cái đầu của từng từ và ở dạng in hoa.

Thứ tự giảng viên của mỗi bộ môn được liệt kê theo đúng thứ tự ban đầu.

**Ví dụ**

 | **Input** | **Ouput** |
|---|---|
| 3  Nguyen Manh Son  Cong nghe phan mem  Vu Hoai Nam  Khoa hoc may tinh  Dang Minh Tuan  An toan thong tin  1  aN | DANH SACH GIANG VIEN THEO TU KHOA aN:  GV01 Nguyen Manh Son CNPM  GV03 Dang Minh Tuan ATTT |

### J05028 - DANH SÁCH DOANH NGHIỆP NHẬN SINH VIÊN THỰC TẬP - 1

Để chuẩn bị cho đợt thực tập tốt nghiệp của sinh viên năm cuối, Khoa CNTT1 trao đổi với các doanh nghiệp đối tác và chốt số lượng sinh viên có thể nhận thực tập.

Hãy sắp xếp các doanh nghiệp theo số lượng sinh viên có thể nhận giảm dần.

**Input**

Dòng đầu ghi số doanh nghiệp.

Mỗi doanh nghiệp ghi trên 3 dòng:

- Mã doanh nghiệp (xâu ký tự không có dấu cách, độ dài không quá 10)
- Tên doanh nghiệp (xâu ký tự độ dài không quá 150)
- Số sinh viên có thể nhận: giá trị nguyên không quá 1000
 
**Output**

Ghi ra danh sách đã được sắp xếp theo số lượng giảm dần, mỗi thông tin ghi trên một dòng. Trong trường hợp cùng số lượng thì sắp xếp theo mã doanh nghiệp (thứ tự từ điển tăng dần).

**Ví dụ**

 | **Input** |
|---|
| 4  VIETTEL  TAP DOAN VIEN THONG QUAN DOI VIETTEL  40  FSOFT  CONG TY TNHH PHAN MEM FPT - FPT SOFTWARE  300  VNPT  TAP DOAN BUU CHINH VIEN THONG VIET NAM  200  SUN  SUN\*  50 |
| **Output** |
| FSOFT CONG TY TNHH PHAN MEM FPT - FPT SOFTWARE 300  VNPT TAP DOAN BUU CHINH VIEN THONG VIET NAM 200  SUN SUN\* 50  VIETTEL TAP DOAN VIEN THONG QUAN DOI VIETTEL 40 |

### J05029 - DANH SÁCH DOANH NGHIỆP NHẬN SINH VIÊN THỰC TẬP - 2

Để chuẩn bị cho đợt thực tập tốt nghiệp của sinh viên năm cuối, Khoa CNTT1 trao đổi với các doanh nghiệp đối tác và chốt số lượng sinh viên có thể nhận thực tập.

Hãy lọc ra các doanh nghiệp nhận số lượng sinh viên trong đoạn \[a,b\].

**Input**

Dòng đầu ghi số doanh nghiệp.

Mỗi doanh nghiệp ghi trên 3 dòng:

- Mã doanh nghiệp (xâu ký tự không có dấu cách, độ dài không quá 10)
- Tên doanh nghiệp (xâu ký tự độ dài không quá 150)
- Số sinh viên có thể nhận: giá trị nguyên không quá 1000
 
Tiếp theo là một dòng ghi số truy vấn Q. Mỗi truy vấn là 2 số nguyên a, b viết trên một dòng trong đó a&lt;b và dữ liệu đảm bảo luôn có ít nhất 1 doanh nghiệp nhận số lượng sinh viên trong đoạn \[a,b\].

**Output**

Ghi ra danh sách đã lọc trong đoạn \[a,b\] và được sắp xếp theo số lượng giảm dần, mỗi thông tin ghi trên một dòng. Trong trường hợp cùng số lượng thì sắp xếp theo mã doanh nghiệp (thứ tự từ điển tăng dần).

**Ví dụ**

 | **Input** |
|---|
| 4  VIETTEL  TAP DOAN VIEN THONG QUAN DOI VIETTEL  40  FSOFT  CONG TY TNHH PHAN MEM FPT - FPT SOFTWARE  300  VNPT  TAP DOAN BUU CHINH VIEN THONG VIET NAM  200  SUN  SUN\*  50  1  30 50 |
| **Output** |
| DANH SACH DOANH NGHIEP NHAN TU 30 DEN 50 SINH VIEN:  SUN SUN\* 50  VIETTEL TAP DOAN VIEN THONG QUAN DOI VIETTEL 40 |

### J05030 - BẢNG ĐIỂM THÀNH PHẦN - 1

Cho dữ liệu bảng điểm thành phần trong đó thông tin của mỗi sinh viên gồm:

- Mã sinh viên (xâu ký tự độ dài không quá 15, không có khoảng trống)
- Tên sinh viên (xâu ký tự, độ dài không quá 50)
- Lớp (xâu ký tự độ dài không quá 15, không có khoảng trống)
- Điểm 1, Điểm 2, Điểm 3: mỗi điểm là một số thực (hệ 10)
 
Hãy sắp xếp lại bảng điểm thành phần theo mã sinh viên (thứ tự từ điển tăng dần).

**Input**

Dòng đầu ghi số sinh viên (không quá 100).

Mỗi sinh viên ghi trên 6 dòng lần lượt là: Mã SV, Họ tên, Lớp, Điểm 1, Điểm 2, Điểm 3.

**Output**

Ghi ra danh sách sinh viên đã sắp xếp theo mã sinh viên.

Mỗi sinh viên ghi trên 1 dòng gồm các thông tin: thứ tự, mã sv, họ tên, lớp, điểm 1, điểm 2, điểm 3. Các thông tin cách nhau đúng một khoảng trống.

Các giá trị điểm ghi ra với đúng 1 chữ số phần thập phân.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  B20DCCN999  Nguyen Van An  D20CQCN04-B  10.0  9.0  8.0  B20DCAT001  Le Van Nam  D20CQAT02-B  6.0  6.0  4.0  B20DCCN111  Tran Hoa Binh  D20CQCN04-B  9.0  5.0  6.0 | 1 B20DCAT001 Le Van Nam D20CQAT02-B 6.0 6.0 4.0  2 B20DCCN111 Tran Hoa Binh D20CQCN04-B 9.0 5.0 6.0  3 B20DCCN999 Nguyen Van An D20CQCN04-B 10.0 9.0 8.0 |

### J05031 - BẢNG ĐIỂM THÀNH PHẦN - 2

Cho dữ liệu bảng điểm thành phần trong đó thông tin của mỗi sinh viên gồm:

- Mã sinh viên (xâu ký tự độ dài không quá 15, không có khoảng trống)
- Họ tên sinh viên (xâu ký tự, độ dài không quá 50)
- Lớp (xâu ký tự độ dài không quá 15, không có khoảng trống)
- Điểm 1, Điểm 2, Điểm 3: mỗi điểm là một số thực (hệ 10)
 
Hãy sắp xếp lại bảng điểm thành phần theo họ tên (thứ tự từ điển tăng dần - so sánh cả xâu ký tự họ tên để sắp xếp, không cần tách tên).

**Input**

Dòng đầu ghi số sinh viên (không quá 100).

Mỗi sinh viên ghi trên 6 dòng lần lượt là: Mã SV, Họ tên, Lớp, Điểm 1, Điểm 2, Điểm 3.

**Output**

Ghi ra danh sách sinh viên đã sắp xếp theo họ tên.

Mỗi sinh viên ghi trên 1 dòng gồm các thông tin: thứ tự, mã sv, họ tên, lớp, điểm 1, điểm 2, điểm 3. Các thông tin cách nhau đúng một khoảng trống. Các giá trị điểm ghi ra với đúng 1 chữ số phần thập phân.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  B20DCCN999  Nguyen Van Nam  D20CQCN04-B  10.0  9.0  8.0  B20DCAT001  Le Van An  D20CQAT02-B  6.0  6.0  4.0  B20DCCN111  Nguyen Van Binh  D20CQCN01-B  9.0  5.0  6.0 | 1 B20DCAT001 Le Van An D20CQAT02-B 6.0 6.0 4.0  2 B20DCCN111 Nguyen Van Binh D20CQCN01-B 9.0 5.0 6.0  3 B20DCCN999 Nguyen Van Nam D20CQCN04-B 10.0 9.0 8.0 |

### J05032 - TRẺ NHẤT – GIÀ NHẤT

Cho một danh sách tên người và ngày tháng năm sinh.

Hãy tìm ra người trẻ nhất và người già nhất.

**Input**

Dòng 1 ghi số N là số người (không quá 100).  
 N dòng tiếp theo, mỗi dòng ghi tên (xâu ký tự không có khoảng trống và không quá 15 ký tự, sau đó là dãy ký tự mô tả ngày tháng năm sinh theo chuẩn dd/mm/yyyy.

**Output**

Dòng đầu ghi ra tên người trẻ nhất.

Dòng thứ 2 ghi ra tên người già nhất.

Dữ liệu đảm bảo không có 2 người nào trùng ngày sinh.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  Nam 01/10/1991  An 30/12/1990  Binh 15/08/1993  Tam 18/09/1990  Truong 20/09/1990 | Binh  Tam |

### J05033 - SẮP XẾP THỜI GIAN

Giá trị độ đo thời gian được biểu diễn bởi ba thành phần: giờ, phút, giây.

Cho N giá trị thời gian, hãy sắp xếp danh sách theo thứ tự tăng dần.

**Input**

Dòng đầu ghi số nguyên dương N (không quá 5000) là số lượng giá trị thời gian cần sắp xếp.

Mỗi giá trị thời gian biểu diễn trên một dòng bằng ba số nguyên dương, lần lượt là số giờ, số phút, số giây. Trong đó số giờ đảm bảo nhỏ hơn 100, số phút và số giây đảm bảo đúng quy tắc (tức là không quá 59).

**Output**

In ra danh sách đã sắp xếp theo thứ tự tăng dần.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  11 20 20  14 20 14  11 15 12 | 11 15 12  11 20 20  14 20 14 |

### J05034 - DANH SÁCH THỰC TẬP - 1

Sinh viên CNTT PTIT đến năm cuối được cử đi thực tập tại các doanh nghiệp.

Thông tin của mỗi sinh viên trong danh sách thực tập bao gồm:

- Số thứ tự: là 1 số nguyên tự động tăng
- Mã sinh viên: là một xâu ký tự không có khoảng trống, không quá 12 ký tự
- Họ tên: là một xâu ký tự họ tên đã chuẩn hóa, không quá 50 ký tự
- Lớp: là một xâu ký tự không có khoảng trống, không quá 10 ký tự
- Email: là một địa chỉ email, không có khoảng trống, không quá 100 ký tự
- Doanh nghiệp: tên viết tắt của doanh nghiệp, không có khoảng trống, không quá 15 ký tự.
 
Hãy viết chương trình đọc vào danh sách thực tập sau đó in danh sách cho từng doanh nghiệp theo yêu cầu.

**Input**

Dòng đầu ghi số N là sinh viên

Mỗi sinh viên ghi trên 5 dòng gồm mã, họ tên, lớp, email và doanh nghiệp.

Không có số thứ tự, cần tự gán theo thứ tự tăng dần từ 1.

Sau khi hết danh sách sinh viên sẽ có một số nguyên Q (không quá 5) cho biết danh sách truy vấn.

Tiếp theo là Q dòng, mỗi dòng ghi tên một doanh nghiệp (đúng như trong danh sách, không có trường hợp nào không tồn tại trong danh sách)

**Output**

Với mỗi doanh nghiệp, liệt kê danh sách sinh viên thực tập ở doanh nghiệp đó theo thứ tự sắp xếp họ tên (so sánh cả xâu họ tên theo thứ tự từ điển, không cần tách riêng phần tên).

Mỗi sinh viên trên một dòng. Mỗi thông tin trong danh sách cách nhau đúng một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 6  B17DCCN016  Le Khac Tuan Anh  D17HTTT2  test1@stu.ptit.edu.vn  VIETTEL  B17DCCN107  Dao Thanh Dat  D17CNPM5  test2@stu.ptit.edu.vn  FPT  B17DCAT092  Cao Danh Huy  D17CQAT04-B  test3@stu.ptit.edu.vn  FPT  B17DCCN388  Cao Sy Hai Long  D17CNPM2  test4@stu.ptit.edu.vn  VNPT  B17DCCN461  Dinh Quang Nghia  D17CNPM2  test5@stu.ptit.edu.vn  FPT  B17DCCN554  Bui Xuan Thai  D17CNPM1  test6@stu.ptit.edu.vn  GAMELOFT  1  FPT | 3 B17DCAT092 Cao Danh Huy D17CQAT04-B test3@stu.ptit.edu.vn FPT  2 B17DCCN107 Dao Thanh Dat D17CNPM5 test2@stu.ptit.edu.vn FPT  5 B17DCCN461 Dinh Quang Nghia D17CNPM2 test5@stu.ptit.edu.vn FPT |

### J05035 - DANH SÁCH THỰC TẬP - 2

Sinh viên CNTT PTIT đến năm cuối được cử đi thực tập tại các doanh nghiệp.

Thông tin của mỗi sinh viên trong danh sách thực tập bao gồm:

- Số thứ tự: là 1 số nguyên tự động tăng
- Mã sinh viên: là một xâu ký tự không có khoảng trống, không quá 12 ký tự
- Họ tên: là một xâu ký tự họ tên đã chuẩn hóa, không quá 50 ký tự
- Lớp: là một xâu ký tự không có khoảng trống, không quá 10 ký tự
- Email: là một địa chỉ email, không có khoảng trống, không quá 100 ký tự
- Doanh nghiệp: tên viết tắt của doanh nghiệp, không có khoảng trống, không quá 15 ký tự.
 
Hãy viết chương trình đọc vào danh sách thực tập sau đó in danh sách cho từng doanh nghiệp theo yêu cầu.

**Input**

Dòng đầu ghi số N là sinh viên

Mỗi sinh viên ghi trên 5 dòng gồm mã, họ tên, lớp, email và doanh nghiệp.

Không có số thứ tự, cần tự gán theo thứ tự tăng dần từ 1.

Sau khi hết danh sách sinh viên sẽ có một số nguyên Q (không quá 5) cho biết danh sách truy vấn.

Tiếp theo là Q dòng, mỗi dòng ghi tên một doanh nghiệp (đúng như trong danh sách, không có trường hợp nào không tồn tại trong danh sách)

**Output**

Với mỗi doanh nghiệp, liệt kê danh sách sinh viên thực tập ở doanh nghiệp đó theo thứ tự sắp xếp mã sinh viên (so sánh theo thứ tự từ điển).

Mỗi sinh viên trên một dòng. Mỗi thông tin trong danh sách cách nhau đúng một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 6  B17DCCN016  Le Khac Tuan Anh  D17HTTT2  test1@stu.ptit.edu.vn  VIETTEL  B17DCCN107  Dao Thanh Dat  D17CNPM5  test2@stu.ptit.edu.vn  FPT  B17DCAT092  Cao Danh Huy  D17CQAT04-B  test3@stu.ptit.edu.vn  FPT  B17DCCN388  Cao Sy Hai Long  D17CNPM2  test4@stu.ptit.edu.vn  VNPT  B17DCCN461  Dinh Quang Nghia  D17CNPM2  test5@stu.ptit.edu.vn  FPT  B17DCCN554  Bui Xuan Thai  D17CNPM1  test6@stu.ptit.edu.vn  GAMELOFT  1  FPT | 3 B17DCAT092 Cao Danh Huy D17CQAT04-B test3@stu.ptit.edu.vn FPT  2 B17DCCN107 Dao Thanh Dat D17CNPM5 test2@stu.ptit.edu.vn FPT  5 B17DCCN461 Dinh Quang Nghia D17CNPM2 test5@stu.ptit.edu.vn FPT |

### J05036 - TÍNH GIÁ BÁN - 1

Cửa hàng tạp hóa cần tính toán các chi phí liên quan để quyết định giá bán. Mỗi mặt hàng có tên hàng, đơn vị tính, đơn giá nhập và số lượng. Các chi phí khác tính như sau:

- *Phí vận chuyển = (đơn giá nhập \* số lượng) \*5%.* Cần làm tròn (round) đến hàng đơn vị.
- *Thành tiền = đơn giá nhập \* số lượng + phí vận chuyển.* Cần làm tròn (round) đến hàng đơn vị.
- Giá bán = Thành tiền + 2% Thành tiền. *(ở đây giá bán được hiểu là tổng số tiền muốn thu về với cả lô hàng hóa đó, không phải giá bán lẻ từng sản phẩm).*
 
Hãy lập bảng tính toán giá bán cho cửa hàng nhé.

**Input**

- Dòng đầu ghi số mặt hàng (không quá 50)
- Mỗi mặt hàng ghi trên 4 dòng lần lượt là: tên hàng, đơn vị tính, đơn giá nhập, số lượng.
 
**Output**

Ghi ra danh sách mặt hàng gồm các thông tin:

- Mã hàng (tự động tăng theo thứ tự nhập, tính từ MH01)
- Tên hàng
- Đơn vị tính
- Phí vận chuyển
- Thành tiền
- Giá bán
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  DUONG  KG  7500  150  TRUNG  CHUC  10000  225  GAO  KG  14000  118  SUA  HOP  48000  430 | MH01 DUONG KG 56250 1181250 1204875  MH02 TRUNG CHUC 112500 2362500 2409750  MH03 GAO KG 82600 1734600 1769292  MH04 SUA HOP 1032000 21672000 22105440 |

### J05037 - TÍNH GIÁ BÁN - 2

Cửa hàng tạp hóa cần tính toán các chi phí liên quan để quyết định giá bán. Mỗi mặt hàng có tên hàng, đơn vị tính, đơn giá nhập và số lượng. Các chi phí khác tính như sau:

- *Phí vận chuyển = (đơn giá nhập \* số lượng) \*5%.* Cần làm tròn (round) đến hàng đơn vị.
- *Thành tiền = đơn giá nhập \* số lượng + phí vận chuyển.* Cần làm tròn (round) đến hàng đơn vị.
- **Giá bán = (Thành tiền + 2% Thành tiền)/số lượng**. *(ở đây giá bán được hiểu là giá bán lẻ từng sản phẩm, làm tròn lên đến đơn vị hàng trăm).*
 
Hãy lập bảng tính toán giá bán lẻ cho cửa hàng.

**Input**

- Dòng đầu ghi số mặt hàng (không quá 50)
- Mỗi mặt hàng ghi trên 4 dòng lần lượt là: tên hàng, đơn vị tính, đơn giá nhập, số lượng.
 
**Output**

Ghi ra danh sách mặt hàng đã được sắp xếp theo giá bán lẻ giảm dần gồm các thông tin:

- Mã hàng (tự động tăng theo thứ tự nhập, tính từ MH01)
- Tên hàng
- Đơn vị tính
- Phí vận chuyển
- Thành tiền
- Giá bán lẻ
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  DUONG  KG  7500  150  TRUNG  CHUC  10000  225  GAO  KG  14000  118  SUA  HOP  48000  430 | MH04 SUA HOP 1032000 21672000 51500  MH03 GAO KG 82600 1734600 15000  MH02 TRUNG CHUC 112500 2362500 10800  MH01 DUONG KG 56250 1181250 8100 |

### J05038 - BẢNG KÊ TIỀN LƯƠNG

Công ty A muốn lập bảng kê tiền lương cho nhân viên.

Quy tắc tính lương như sau:

- Lương tháng = Lương ngày \* số ngày công
- Thưởng
    - Nếu số ngày công &gt;=25: Thưởng 20%\* Lương Tháng
    - Nếu số ngày công &gt;=22: Thưởng 10%\* Lương Tháng
    - Nếu số ngày công &lt; 22 : Không Thưởng
- Phụ cấp chức vụ:
    - Nếu chức vụ là GD: 250000
    - PGĐ: 200000
    - TP:180000
    - NV: 150000
 
Hãy lập bảng kê chi tiết cho từng nhân viên trong công ty và tính tổng số chi phí tiền lương trong tháng.

**Input**

- Dòng đầu ghi số nhân viên (không quá 50)
- Mỗi nhân viên ghi trên 4 dòng
    - Họ tên
    - Lương ngày
    - Số ngày công
    - Chức vụ
 
**Output**

Ghi ra danh sách nhân viên đã được tính lương gồm các thông tin:

- Mã nhân viên (tự động tăng theo thứ tự nhập, tính từ NV01)
- Tên nhân viên
- Lương tháng
- Thưởng
- Phụ cấp chức vụ
- Thực lĩnh
 
Dòng cuối ghi tổng chi phí tiền lương (theo mẫu trong ví dụ).

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  Cao Van Vu  50000  26  GD  Bui Thi Trang  45000  23  PGD  Do Van Truong  40000  25  PGD  Nguyen Van Cam  37000  26  TP  Truong Thi Tu Linh  45000  22  NV | NV01 Cao Van Vu 1300000 260000 250000 1810000  NV02 Bui Thi Trang 1035000 103500 200000 1338500  NV03 Do Van Truong 1000000 200000 200000 1400000  NV04 Nguyen Van Cam 962000 192400 180000 1334400  NV05 Truong Thi Tu Linh 990000 99000 150000 1239000  Tong chi phi tien luong: 7121900 |

### J05040 - LẬP BẢNG TÍNH CÔNG

Thông tin về nhân viên bao gồm:

- Mã nhân viên (tự động tăng theo thứ tự nhập, tính từ NV01)
- Họ và tên
- Lương cơ bản mỗi ngày công
- Số ngày công
- Chức vụ
 
Tiền lương được tính bằng lương cơ bản nhân với số ngày công.

Giả sử quy tắc tính tiền thưởng như sau:

- Số ngày công từ 25 trở lên thì thưởng 20% tiền lương
- Số ngày công từ 22 đến dưới 25 thì thưởng 10% tiền lương
- Dưới 22 ngày công thì không có thưởng.
 
Mỗi nhân viên có thể có thêm phụ cấp chức vụ:

- GD: 250000
- PGD: 200000
- TP: 180000
- NV: 150000
 
Hãy nhập thông tin các nhân viên và tính toán thu nhập theo quy tắc trên.

**Input**

Dòng đầu ghi số nhân viên.

Mỗi nhân viên gồm 4 dòng lần lượt ghi Họ tên, lương cơ bản, số ngày công và chức vụ.

**Output**

Ghi ra danh sách nhân viên theo thứ tự nhập, mỗi nhân viên trên một dòng gồm: mã nhân viên, tên nhân viên, lương tháng, thưởng, phụ cấp và thu nhập. Các thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Cao Van Vu  50000  26  GD  Do Van Truong  40000  25  PGD  Truong Thi Tu Linh  45000  22  NV | NV01 Cao Van Vu 1300000 260000 250000 1810000  NV02 Do Van Truong 1000000 200000 200000 1400000  NV03 Truong Thi Tu Linh 990000 99000 150000 1239000 |

### J05041 - SẮP XẾP BẢNG TÍNH CÔNG

Thông tin về nhân viên bao gồm:

- Mã nhân viên (tự động tăng theo thứ tự nhập, tính từ NV01)
- Họ và tên
- Lương cơ bản mỗi ngày công
- Số ngày công
- Chức vụ
 
Tiền lương được tính bằng lương cơ bản nhân với số ngày công.

Giả sử quy tắc tính tiền thưởng như sau:

- Số ngày công từ 25 trở lên thì thưởng 20% tiền lương
- Số ngày công từ 22 đến dưới 25 thì thưởng 10% tiền lương
- Dưới 22 ngày công thì không có thưởng.
 
Mỗi nhân viên có thể có thêm phụ cấp chức vụ:

- GD: 250000
- PGD: 200000
- TP: 180000
- NV: 150000
 
Hãy nhập thông tin các nhân viên, tính toán thu nhập theo quy tắc trên và sắp xếp theo thu nhập giảm dần (không có 2 nhân viên nào có thu nhập đúng bằng nhau).

**Input**

Dòng đầu ghi số nhân viên.

Mỗi nhân viên gồm 4 dòng lần lượt ghi Họ tên, lương cơ bản, số ngày công và chức vụ.

**Output**

Ghi ra danh sách nhân viên đã sắp xếp, mỗi nhân viên trên một dòng gồm: mã nhân viên, tên nhân viên, lương tháng, thưởng, phụ cấp và thu nhập. Các thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Cao Van Vu  50000  26  GD  Do Van Truong  40000  25  PGD  Truong Thi Tu Linh  45000  22  NV | NV01 Cao Van Vu 1300000 260000 250000 1810000  NV02 Do Van Truong 1000000 200000 200000 1400000  NV03 Truong Thi Tu Linh 990000 99000 150000 1239000 |

### J05042 - BẢNG XẾP HẠNG

Trên cổng thực hành trực tuyến của Học viện Công nghệ Bưu chính Viễn thông có danh sách sinh viên trong lớp được xếp hạng để đánh giá kết quả. Mỗi sinh viên có họ tên, số bài làm đúng, tổng số lượt submit. Hãy sắp xếp danh sách sinh viên để có bảng xếp hạng môn học

Thứ tự sắp xếp như sau:

- Sinh viên có số bài làm đúng nhiều hơn xếp trước, nếu có cùng số bài làm đúng thì ưu tiên sinh viên có số lượt submit ít hơn.
- Sinh viên có cùng hạng, xếp họ tên ưu tiên theo thứ tự từ điển lên trước.
 
**Input**

Dòng đầu tiên đưa vào sĩ số lớp N.

Những dòng kế tiếp đưa vào N sinh viên. Mỗi sinh viên gồm 2 dòng dữ liệu, dòng thứ nhất là họ tên của sinh viên (S) *đã được chuẩn hóa*, dòng thứ hai gồm hai số nguyên liên tiếp C là số bài làm đúng, T là số lượt submit.

N, S thỏa mãn ràng buộc: 1≤ N ≤100; 1≤ Length(S)≤100

C, T thỏa mãn ràng buộc C&lt;500, T &lt; 109

**Output**

Đưa ra bảng xếp hạng danh sách sinh viên đã sắp xếp

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2    Nguyen Van Nam    168 600    Tran Thi Ngoc    168 600 | Nguyen Van Nam 168 600    Tran Thi Ngoc 168 600 |

### J05043 - TÍNH THU NHẬP CHO NHÂN VIÊN

Thu nhập của cán bộ công nhân viên trong công ty X được tính bao gồm lương chính (bằng lương cơ bản nhân số ngày công) cộng với phụ cấp chức vụ (được tính riêng theo từng chức vụ cụ thể).

Phụ cấp chức vụ được quy định như sau (đơn vị nghìn đồng):

- GD: 500
- PGD: 400
- TP: 300
- KT: 250
- Các trường hợp khác: 100.
 
Mỗi tháng sẽ có tạm ứng. Quy tắc tính tạm ứng như sau:

- Nếu (Phụ cấp chức vụ + Lương)\*2/3 &lt; 25000 thì Tạm ứng = (Phụ cấp chức vụ + Lương)\*2/3 (làm tròn - round - đến hàng ngàn)
- Ngược lại: Tạm ứng = 25000
 
Viết chương trình nhập danh sách nhân viên và lập bảng kê thu nhập trong tháng.

**Input**

- Dòng đầu ghi số nhân viên (không quá 50)
- Mỗi nhân viên ghi trên 4 dòng gồm: 
    - Họ và tên (không quá 50 chữ cái)
    - Chức vụ
    - Lương cơ bản
    - Số ngày công
- Mã nhân viên cần được tự điền tăng dần, bắt đầu từ NV01
 
**Output**

Ghi ra danh sách nhân viên theo đúng thứ tự ban đầu. Mỗi nhân viên bao gồm các thông tin:

- Mã nhân viên
- Họ và tên
- Phụ cấp chức vụ
- Lương chính
- Tạm ứng
- Còn lại
 
Các thông tin viết cách nhau một khoảng trống

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  Tran Thi Yen  NV  1000  24  Nguyen Van Thanh  BV  1000  30  Doan Truong An  TP  3000  25  Le Thanh  GD  5000  28 | NV01 Tran Thi Yen 100 24000 16000 8100  NV02 Nguyen Van Thanh 100 30000 20000 10100  NV03 Doan Truong An 300 75000 25000 50300  NV04 Le Thanh 500 140000 25000 115500 |

### J05044 - LIỆT KÊ NHÂN VIÊN THEO CHỨC VỤ

Thu nhập của cán bộ công nhân viên trong công ty X được tính bao gồm lương chính (bằng lương cơ bản nhân số ngày công) cộng với phụ cấp chức vụ (được tính riêng theo từng chức vụ cụ thể).

Phụ cấp chức vụ được quy định như sau (đơn vị nghìn đồng):

- GD: 500
- PGD: 400
- TP: 300
- KT: 250
- Các trường hợp khác: 100.
 
Mỗi tháng sẽ có tạm ứng. Quy tắc tính tạm ứng như sau:

- Nếu (Phụ cấp chức vụ + Lương)\*2/3 &lt; 25000 thì Tạm ứng = (Phụ cấp chức vụ + Lương)\*2/3 (làm tròn - round - đến hàng ngàn)
- Ngược lại: Tạm ứng = 25000
 
Viết chương trình nhập danh sách nhân viên và lập bảng kê thu nhập trong tháng theo chức vụ.

**Input**

- Dòng đầu ghi số nhân viên (không quá 50)
- Mỗi nhân viên ghi trên 4 dòng gồm: 
    - Họ và tên (không quá 50 chữ cái)
    - Chức vụ
    - Lương cơ bản
    - Số ngày công
- Mã nhân viên cần được tự điền tăng dần, bắt đầu từ NV01
- Dòng cuối cùng ghi chức vụ cần liệt kê
 
**Output**

Ghi ra danh sách nhân viên có chức vụ phù hợp với từ khóa cần tìm (theo đúng thứ tự ban đầu). Mỗi nhân viên bao gồm các thông tin:

- Mã nhân viên
- Họ và tên
- Phụ cấp chức vụ
- Lương chính
- Tạm ứng
- Còn lại
 
Các thông tin viết cách nhau một khoảng trống

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  Tran Thi Yen  NV  1000  24  Nguyen Van Thanh  BV  1000  30  Doan Truong An  TP  3000  25  Le Thanh  GD  5000  28  TP | NV03 Doan Truong An 300 75000 25000 50300 |

### J05045 - SẮP XẾP NHÂN VIÊN THEO THU NHẬP

Thu nhập của cán bộ công nhân viên trong công ty X được tính bao gồm lương chính (bằng lương cơ bản nhân số ngày công) cộng với phụ cấp chức vụ (được tính riêng theo từng chức vụ cụ thể).

Phụ cấp chức vụ được quy định như sau (đơn vị nghìn đồng):

- GD: 500
- PGD: 400
- TP: 300
- KT: 250
- Các trường hợp khác: 100.
 
Mỗi tháng sẽ có tạm ứng. Quy tắc tính tạm ứng như sau:

- Nếu (Phụ cấp chức vụ + Lương)\*2/3 &lt; 25000 thì Tạm ứng = (Phụ cấp chức vụ + Lương)\*2/3 (làm tròn - round - đến hàng ngàn)
- Ngược lại: Tạm ứng = 25000
 
Viết chương trình nhập danh sách nhân viên sắp xếp theo thu nhập giảm dần.

**Input**

- Dòng đầu ghi số nhân viên (không quá 50)
- Mỗi nhân viên ghi trên 4 dòng gồm: 
    - Họ và tên (không quá 50 chữ cái)
    - Chức vụ
    - Lương cơ bản
    - Số ngày công
- Mã nhân viên cần được tự điền tăng dần, bắt đầu từ NV01
 
**Output**

Ghi ra danh sách nhân viên theo thứ tự thu nhập giảm dần. Nếu 2 nhân viên có thu nhập bằng nhau thì nhân viên nào có mã nhỏ hơn sẽ liệt kê trước. . Mỗi nhân viên bao gồm các thông tin:

- Mã nhân viên
- Họ và tên
- Phụ cấp chức vụ
- Lương chính
- Tạm ứng
- Còn lại
 
Các thông tin viết cách nhau một khoảng trống

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  Tran Thi Yen  NV  1000  24  Nguyen Van Thanh  BV  1000  30  Doan Truong An  TP  3000  25  Le Thanh  GD  5000  28 | NV04 Le Thanh 500 140000 25000 115500  NV03 Doan Truong An 300 75000 25000 50300  NV02 Nguyen Van Thanh 100 30000 20000 10100  NV01 Tran Thi Yen 100 24000 16000 8100 |

### J05046 - BẢNG KÊ NHẬP KHO

Một cửa hàng điện máy nhập các mặt hàng và muốn thống kê chi phí. Mỗi lô mặt hàng sẽ có tiền chiết khấu và được trừ vào tổng giá tiền của hóa đơn nhập lô hàng đó.

Tiền chiết khấu được tính như sau:

 *Tiền chiết khấu = Đơn giá \* Số lượng \* Phần trăm chiết khấu.*

Với:

 Phần trăm chiết khấu là 5% nếu số lượng &gt; 10,

 Phần trăm chiết khấu là 2% nếu 8 &lt;= số lượng &lt;= 10,

 Phần trăm chiết khấu là 1% nếu 5 &lt;= số lượng &lt;8,

 Phần trăm chiết khấu là 0 nếu số lượng &lt; 5.

Ngoài ra, để dễ quản lý, nhân viên nhập kho sẽ gán mã mặt hàng cho từng lô hàng. Mã hàng sẽ được tạo ra bằng hai ký tự đầu tiên của tên hàng kèm theo số thứ tự tính từ 01 (giả sử không có nhiều hơn 9 lô hàng cùng loại trong đợt nhập này). Hãy tính thành tiền chi tiết cho các mặt hàng.

**Input**

- Dòng đầu ghi số lượng lô hàng
- Mỗi lô hàng ghi trên 3 dòng gồm: 
    - Tên hàng
    - Số lượng
    - Đơn giá
 
**Output**

Ghi ra danh sách mặt hàng đã tính thành tiền. Thông tin về mỗi lô hàng gồm:

- Mã hàng
- Tên hàng
- Tiền chiết khấu
- Thành tiền
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  May lanh SANYO  12  4000000  Dien thoai Samsung  30  3230000  Dien thoai Nokia  18  1240000 | ML01 May lanh SANYO 2400000 45600000  DT01 Dien thoai Samsung 4845000 92055000  DT02 Dien thoai Nokia 1116000 21204000 |

### J05047 - BẢNG KÊ NHẬP KHO SẮP XẾP THEO CHIẾT KHẤU

Một cửa hàng điện máy nhập các mặt hàng và muốn thống kê chi phí. Mỗi lô mặt hàng sẽ có tiền chiết khấu và được trừ vào tổng giá tiền của hóa đơn nhập lô hàng đó.

Tiền chiết khấu được tính như sau:

 *Tiền chiết khấu = Đơn giá \* Số lượng \* Phần trăm chiết khấu.*

Với:

 Phần trăm chiết khấu là 5% nếu số lượng &gt; 10,

 Phần trăm chiết khấu là 2% nếu 8 &lt;= số lượng &lt;= 10,

 Phần trăm chiết khấu là 1% nếu 5 &lt;= số lượng &lt;8,

 Phần trăm chiết khấu là 0 nếu số lượng &lt; 5.

Ngoài ra, để dễ quản lý, nhân viên nhập kho sẽ gán mã mặt hàng cho từng lô hàng. Mã hàng sẽ được tạo ra bằng hai ký tự đầu tiên của tên hàng kèm theo số thứ tự tính từ 01 (giả sử không có nhiều hơn 9 lô hàng cùng loại trong đợt nhập này). Hãy tính thành tiền chi tiết cho các mặt hàng sau đó sắp xếp theo chiết khấu giảm dần. (Dữ liệu vào đảm bảo không có 2 lô hàng nào được chiết khấu bằng nhau).

**Input**

- Dòng đầu ghi số lượng lô hàng
- Mỗi lô hàng ghi trên 3 dòng gồm: 
    - Tên hàng
    - Số lượng
    - Đơn giá
 
**Output**

Ghi ra danh sách mặt hàng đã tính thành tiền và sắp xếp theo chiết khấu giảm dần. Thông tin về mỗi lô hàng gồm:

- Mã hàng
- Tên hàng
- Tiền chiết khấu
- Thành tiền
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  May lanh SANYO  12  4000000  Dien thoai Samsung  30  3230000  Dien thoai Nokia  18  1240000 | DT01 Dien thoai Samsung 4845000 92055000  ML01 May lanh SANYO 2400000 45600000  DT02 Dien thoai Nokia 1116000 21204000 |

### J05048 - BẢNG THEO DÕI NHẬP XUẤT HÀNG

Người quản lý kho của một kho hàng nông sản tiến hành phân loại và gán mã cho các sản phẩm nhập/xuất trong tháng.

Với mã hàng dạng 5 chữ cái, các quy tắc liên quan đến gán mã hàng được mô tả như sau:

**Số lượng Xuất hàng** được tính như sau:

- Nếu Mã hàng có ký tự đầu là A thì Xuất = 60% \* Nhập
- Nếu Mã hàng có ký tự đầu là B thì Xuất = 70% \* Nhập
 
*Chú ý: Số lượng xuất cần được làm tròn (round) đến hàng đơn vị sau khi tính theo công thức trên, không thể xuất với số lượng lẻ phần thập phân.*

Tính **Đơn giá** như sau:

- Nếu Mã hàng có ký tự cuối là Y thì Đơn giá = 110000
- Nếu Mã hàng có ký tự cuối là N thì Đơn giá = 135000
 
**Tiền = Xuất \* Đơn giá.**

**Thuế** được tính như sau:

- Nếu Mã hàng có ký tự đầu là A và ký tự cuối là Y thì Thuế = 8% của Tiền
- Nếu Mã hàng có ký tự đầu là A và ký tự cuối là N thì Thuế = 11% của Tiền
- Nếu Mã hàng có ký tự đầu là B và ký tự cuối là Y thì Thuế = 17% của Tiền
- Nếu Mã hàng có ký tự đầu là B và ký tự cuối là N thì Thuế = 22% của Tiền.
 
Cho mã hàng và số lượng nhập. Viết chương trình lập bảng theo dõi chi tiết theo quy tắc trên.

**Input**

Dòng đâu ghi số mã hàng. Mỗi mã hàng chỉ có 2 dòng gồm mã và số lượng nhập.

**Output**

Tính toán và in ra thông tin chi tiết từng mã hàng gồm:

- Mã hàng (đảm bảo đúng quy tắc, chữ cái đầu là A hoặc B, chữ cái cuối là Y hoặc N).
- Số lượng nhập
- Số lượng xuất
- Đơn giá
- Tiền
- Thuế
 
Các thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  A001Y  1000  B012N  2500  B003Y  4582 | A001Y 1000 600 110000 66000000 5280000  B012N 2500 1750 135000 236250000 51975000  B003Y 4582 3207 110000 352770000 59970900 |

### J05049 - LIỆT KÊ NHẬP XUẤT HÀNG THEO NHÓM

Người quản lý kho của một kho hàng nông sản tiến hành phân loại và gán mã cho các sản phẩm nhập/xuất trong tháng.

Với mã hàng dạng 5 chữ cái, các quy tắc liên quan đến gán mã hàng được mô tả như sau:

**Số lượng Xuất hàng** được tính như sau:

- Nếu Mã hàng có ký tự đầu là A thì Xuất = 60% \* Nhập
- Nếu Mã hàng có ký tự đầu là B thì Xuất = 70% \* Nhập
 
*Chú ý: Số lượng xuất cần được làm tròn (round) đến hàng đơn vị sau khi tính theo công thức trên, không thể xuất với số lượng lẻ phần thập phân.*

Tính **Đơn giá** như sau:

- Nếu Mã hàng có ký tự cuối là Y thì Đơn giá = 110000
- Nếu Mã hàng có ký tự cuối là N thì Đơn giá = 135000
 
**Tiền = Xuất \* Đơn giá.**

**Thuế** được tính như sau:

- Nếu Mã hàng có ký tự đầu là A và ký tự cuối là Y thì Thuế = 8% của Tiền
- Nếu Mã hàng có ký tự đầu là A và ký tự cuối là N thì Thuế = 11% của Tiền
- Nếu Mã hàng có ký tự đầu là B và ký tự cuối là Y thì Thuế = 17% của Tiền
- Nếu Mã hàng có ký tự đầu là B và ký tự cuối là N thì Thuế = 22% của Tiền.
 
Cho mã hàng và số lượng nhập. Viết chương trình lập bảng theo dõi chi tiết theo quy tắc trên sau đó liệt kê theo nhóm mặt hàng (A hoặc B).

**Input**

Dòng đâu ghi số mã hàng. Mỗi mã hàng chỉ có 2 dòng gồm mã và số lượng nhập.

Dòng cuối ghi nhóm cần liệt kê (chữ cái A hoặc B).

Dữ liệu đảm bảo trong cùng nhóm không có mặt hàng nào có thuế bằng nhau.

**Output**

Tính toán và in ra thông tin chi tiết từng mã hàng theo nhóm được yêu cầu, và đã được sắp xếp theo Thuế giảm dần gồm:

- Mã hàng (đảm bảo đúng quy tắc, chữ cái đầu là A hoặc B, chữ cái cuối là Y hoặc N).
- Số lượng nhập
- Số lượng xuất (làm tròn - round - đến đơn vị)
- Đơn giá
- Tiền
- Thuế
 
Các thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  A001Y  1000  B012N  2500  B003Y  4582  B | B003Y 4582 3207 110000 352770000 59970900  B012N 2500 1750 135000 236250000 51975000 |

### J05050 - TÍNH TIỀN ĐIỆN

Để thuận tiện cho việc ghi chỉ số công tơ, nhân viên “trèo cột” đã có sẵn một bảng trong đó ghi thứ tự khác hàng, loại khách hàng (Loại SD) và chỉ số cũ. Anh ta chỉ cần ghi chỉ số mới là xong. Giả sử mã khách hàng được gán theo thứ tự, tính từ KH01.

Các quy tắc tính tiền điện được mô tả như sau:

**Hệ số** được tính như sau:

\- Nếu Loại SD là "KD" thì Hệ số = 3

\- Nếu Loại SD là "NN" thì Hệ số = 5

\- Nếu Loại SD là "TT" thì Hệ số = 4

\- Nếu Loại SD là "CN" thì Hệ số = 2

3\) **Thành tiền** = (Chỉ số mới - Chỉ số cũ) \* Hệ số \*550

4\) Tính **Phụ trội** như sau:

\- Phụ trội = 0 nếu (Chỉ số mới - Chỉ số cũ) &lt; 50

\- Phụ trội = Thành tiền \* 35% nếu 50 &lt;= (Chỉ số mới - Chỉ số cũ) &lt;= 100

\- Phụ trội = Thành tiền \* 100% nếu (Chỉ số mới - Chỉ số cũ) &gt; 100

5\) **Tổng tiền phải trả**= Phụ trội + Thành tiền.

Hãy lập bảng kê tính tiền chi tiết cho từng khách hàng.

**Input**

Dòng đầu ghi số khách hàng. Mỗi khách hàng ghi trên 3 dòng gồm Loại SD, chỉ số cũ và chỉ số mới.

**Output**

Ghi ra danh sách khách hàng theo thứ tự nhập gồm các thông tin (cách nhau 1 khoảng trống):

- Mã khách hàng
- Hệ số
- Thành tiền
- Phụ trội
- Tổng tiền phải trả
 
Chú ý: giá trị Phụ trội cần làm tròn (round) đến số nguyên gần nhất.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  KD  400  555  NN  58  400  CN  150  700 | KH01 3 255750 255750 511500  KH02 5 940500 940500 1881000  KH03 2 605000 605000 1210000 |

### J05051 - SẮP XẾP BẢNG TÍNH TIỀN ĐIỆN

Để thuận tiện cho việc ghi chỉ số công tơ, nhân viên “trèo cột” đã có sẵn một bảng trong đó ghi thứ tự khác hàng, loại khách hàng (Loại SD) và chỉ số cũ. Anh ta chỉ cần ghi chỉ số mới là xong. Giả sử mã khách hàng được gán theo thứ tự, tính từ KH01.

Các quy tắc tính tiền điện được mô tả như sau:

**Hệ số** được tính như sau:

\- Nếu Loại SD là "KD" thì Hệ số = 3

\- Nếu Loại SD là "NN" thì Hệ số = 5

\- Nếu Loại SD là "TT" thì Hệ số = 4

\- Nếu Loại SD là "CN" thì Hệ số = 2

3\) **Thành tiền** = (Chỉ số mới - Chỉ số cũ) \* Hệ số \*550

4\) Tính **Phụ trội** như sau:

\- Phụ trội = 0 nếu (Chỉ số mới - Chỉ số cũ) &lt; 50

\- Phụ trội = Thành tiền \* 35% nếu 50 &lt;= (Chỉ số mới - Chỉ số cũ) &lt;= 100

\- Phụ trội = Thành tiền \* 100% nếu (Chỉ số mới - Chỉ số cũ) &gt; 100

5\) **Tổng tiền phải trả**= Phụ trội + Thành tiền.

Hãy lập bảng kê tính tiền chi tiết cho từng khách hàng sau đó sắp xếp theo tổng tiền phải trả giảm dần.

**Input**

Dòng đầu ghi số khách hàng. Mỗi khách hàng ghi trên 3 dòng gồm Loại SD, chỉ số cũ và chỉ số mới.

**Output**

Ghi ra danh sách khách hàng đã sắp xếp theo tổng tiền phải trả giảm dần gồm các thông tin (cách nhau 1 khoảng trống):

- Mã khách hàng
- Hệ số
- Thành tiền
- Phụ trội
- Tổng tiền phải trả
 
Chú ý: giá trị Phụ trội cần làm tròn (round) đến số nguyên gần nhất. Dữ liệu đảm bảo không có hai khách hàng nào có tổng tiền phải trả bằng nhau.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  KD  400  555  NN  58  400  CN  150  700 | KH02 5 940500 940500 1881000  KH03 2 605000 605000 1210000  KH01 3 255750 255750 511500 |

### J05052 - TRA CỨU ĐƠN HÀNG

Cửa hàng quần áo thời trang muốn lưu trữ thông tin về các đơn hàng dưới dạng các thông tin ngắn gọn nhất có thể. Mã đơn hàng do đó chứa khá nhiều thông tin:

- Chữ cái đầu tiên giúp chủ cửa hàng biết tên mặt hàng
- Ba chữ số tiếp theo là số thứ tự đơn hàng
- Chữ số cuối cùng là mã loại: chỉ có 2 loại là 1 hoặc 2.
 
Dựa trên mã loại, mặt hàng sẽ được giảm giá theo quy tắc sau:

- nếu Mã loại là 1 thì Giảm giá = 50%\*Đơn giá \* Số lượng
- nếu Mã loại là 2 thì Giảm giá = 30%\*Đơn giá \* Số lượng
 
Hãy tính toán thành tiền cho từng mã đơn hàng.

**Input**

- Dòng đầu ghi số lượng đơn hàng
- Mỗi đơn hàng ghi trên 4 dòng gồm: 
    - Tên hàng (độ dài không quá 30)
    - Mã đơn hàng hàng: có đúng 5 ký tự theo mẫu đã mô tả
    - Đơn giá
    - Số lượng
 
**Output**

Ghi ra danh sách mặt hàng sau khi tính toán, thứ tự giữ nguyên như lúc nhập. Các thông tin cần hiển thị gồm:

- Tên hàng
- Mã đơn hàng
- Số thứ tự đơn hàng (đủ 3 chữ số)
- Giảm giá
- Thành tiền
 
Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Kaki 2  K0252  80000  15  Jean 1  J2011  200000  24  Jean 2  J0982  150000  12 | Kaki 2 K0252 025 360000 840000  Jean 1 J2011 201 2400000 2400000  Jean 2 J0982 098 540000 1260000 |

### J05053 - SẮP XẾP ĐƠN HÀNG

Cửa hàng quần áo thời trang muốn lưu trữ thông tin về các đơn hàng dưới dạng các thông tin ngắn gọn nhất có thể. Mã đơn hàng do đó chứa khá nhiều thông tin:

- Chữ cái đầu tiên giúp chủ cửa hàng biết tên mặt hàng
- Ba chữ số tiếp theo là số thứ tự đơn hàng
- Chữ số cuối cùng là mã loại: chỉ có 2 loại là 1 hoặc 2.
 
Dựa trên mã loại, mặt hàng sẽ được giảm giá theo quy tắc sau:

- nếu Mã loại là 1 thì Giảm giá = 50%\*Đơn giá \* Số lượng
- nếu Mã loại là 2 thì Giảm giá = 30%\*Đơn giá \* Số lượng
 
Hãy tính toán thành tiền cho từng mã đơn hàng.

**Input**

- Dòng đầu ghi số lượng đơn hàng
- Mỗi đơn hàng ghi trên 4 dòng gồm: 
    - Tên hàng (độ dài không quá 30)
    - Mã đơn hàng hàng: có đúng 5 ký tự theo mẫu đã mô tả
    - Đơn giá
    - Số lượng
 
Dữ liệu vào đảm bảo không có 2 đơn hàng nào có số thứ tự bằng nhau.

**Output**

Ghi ra danh sách mặt hàng sau khi tính toán và sắp xếp theo thứ tự đơn hàng từ nhỏ đến lớn. Các thông tin cần hiển thị gồm:

- Tên hàng
- Mã đơn hàng
- Số thứ tự đơn hàng (đủ 3 chữ số)
- Giảm giá
- Thành tiền
 
Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Kaki 2  K0252  80000  15  Jean 1  J2011  200000  24  Jean 2  J0982  150000  12 | Kaki 2 K0252 025 360000 840000  Jean 2 J0982 098 540000 1260000  Jean 1 J2011 201 2400000 2400000 |

### J05054 - XẾP HẠNG HỌC SINH

Trước khi có quy định mới về việc không cho điểm từng môn và tính trung bình ở cấp học Trung học cơ sở thì Xếp hạng học sinh trong lớp vẫn là một trong những thông tin rất quan trọng với phụ huynh và học sinh. Đôi khi chỉ vì tăng giảm một vài thứ hạng trong lớp mà học sinh được khen thưởng hoặc chê bai học hành sa sút.

Hãy viết chương trình tính toán và xếp loại học lực và hếp hạng học sinh theo điểm trung bình.

**Input**

- Dòng đầu ghi số học sinh trong lớp (không quá 50)
- Thông tin về mỗi học sinh gồm 2 dòng
    - Họ và tên
    - Điểm trung bình (số thực, chính xác đến 1 số phần thập phân, đảm bảo trong phạm vi từ 0 đến 10).
 
**Output**

Tính toán và in danh sách học sinh đã được xếp hạng (thứ tự vẫn giữ nguyên như thứ tự ban đầu). Với mỗi học sinh cần ghi ra các thông tin:

- Mã học sinh (tự động gán, tính từ HS01)
- Họ và tên
- ĐTB
- Xếp loại
    - Nhỏ hơn 5: Yeu
    - Từ 5 đến dưới 7: Trung Binh
    - Từ 7 đến dưới 9: Kha
    - Từ 9 trở lên: Gioi
- Xếp hạng
    - Chú ý nếu 2 học sinh bằng điểm thì xếp hạng bằng nhau. Ví dụ có 2 học sinh cùng xếp thứ 10 thì học sinh tiếp theo có điểm thấp hơn 2 bạn đó sẽ xếp thứ 12.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Tran Minh Hieu  5.9  Nguyen Bao Trung  8.6  Le Hong Ha  9.2 | HS01 Tran Minh Hieu 5.9 Trung Binh 3  HS02 Nguyen Bao Trung 8.6 Kha 2  HS03 Le Hong Ha 9.2 Gioi 1 |

### J05055 - XẾP HẠNG VẬN ĐỘNG VIÊN - 1

Cuộc thi chạy được dành cho tất cả mọi người ở tất cả các độ tuổi. Ban tổ chức muốn thêm tính hấp dẫn bằng cách có ưu tiên cho vận động viên cao tuổi.

- Nếu dưới 18 tuổi: không ưu tiên
- Nếu từ 18 tuổi đến dưới 25 tuổi : ưu tiên 1 giây
- Nếu từ 25 tuổi đến 32 tuổi : ưu tiên 2 giây
- Nếu từ 32 tuổi trở lên: ưu tiên 3 giây
- Trong đó tuổi dựa vào năm sinh
 
Hãy viết chương trình tính toán thành tích và xếp hạng các vận động viên.

**Input**

Dòng đầu thi số vận động viên (không quá 50).

Mỗi vận động viên được ghi trên 4 dòng gồm:

- Họ tên
- Ngày sinh (dạng dd/mm/yyyy)
- Thời gian xuất phát (dạng hh:mm:ss)
- Thời gian đến đích (dạng hh:mm:ss)
 
**Output**

Ghi ra danh sách vận động viên đã xếp hạng theo đúng thứ tự nhập. Mỗi VĐV bao gồm:

- Mã (tính từ VDV01)
- Họ tên
- Thành tích thực tế (hh:mm:ss)
- Ưu tiên (hh:mm:ss)
- Thành tích để xếp hạng – đã tính ưu tiên (hh:mm:ss)
- Xếp hạng (chú ý: cùng thành tích thì sẽ xếp cùng một hạng)
 
**Ví dụ**

 | **Input** |
|---|
| 3  Nguyen Van Thanh  20/03/1990  07:00:00  07:10:01  Nguyen Hoa Binh  01/10/1993  07:02:00  07:11:20  Le Thanh Van  15/03/1998  07:05:00  07:15:30 |
| **Output** |
| VDV01 Nguyen Van Thanh 00:10:01 00:00:02 00:09:59 2  VDV02 Nguyen Hoa Binh 00:09:20 00:00:02 00:09:18 1  VDV03 Le Thanh Van 00:10:30 00:00:01 00:10:29 3 |

### J05056 - XẾP HẠNG VẬN ĐỘNG VIÊN - 2

Cuộc thi chạy được dành cho tất cả mọi người ở tất cả các độ tuổi. Ban tổ chức muốn thêm tính hấp dẫn bằng cách có ưu tiên cho vận động viên cao tuổi.

- Nếu dưới 18 tuổi: không ưu tiên
- Nếu từ 18 tuổi đến dưới 25 tuổi : ưu tiên 1 giây
- Nếu từ 25 tuổi đến 32 tuổi : ưu tiên 2 giây
- Nếu từ 32 tuổi trở lên: ưu tiên 3 giây
- Trong đó tuổi dựa vào năm sinh
 
Hãy viết chương trình tính toán thành tích và xếp hạng các vận động viên.

**Input**

Dòng đầu thi số vận động viên (không quá 50).

Mỗi vận động viên được ghi trên 4 dòng gồm:

- Họ tên
- Ngày sinh (dạng dd/mm/yyyy)
- Thời gian xuất phát (dạng hh:mm:ss)
- Thời gian đến đích (dạng hh:mm:ss)
 
**Output**

Ghi ra danh sách vận động viên đã xếp hạng đã sắp xếp theo xếp hạng, từ người xếp hạng 1 đến hết. Mỗi VĐV bao gồm:

- Mã (tính từ VDV01)
- Họ tên
- Thành tích thực tế (hh:mm:ss)
- Ưu tiên (hh:mm:ss)
- Thành tích để xếp hạng – đã tính ưu tiên (hh:mm:ss)
- Xếp hạng (chú ý: cùng thành tích thì sẽ xếp cùng một hạng)
 
**Ví dụ**

 | **Input** |
|---|
| 3  Nguyen Van Thanh  20/03/1990  07:00:00  07:10:01  Nguyen Hoa Binh  01/10/1993  07:02:00  07:11:20  Le Thanh Van  15/03/1998  07:05:00  07:15:30 |
| **Output** |
| VDV02 Nguyen Hoa Binh 00:09:20 00:00:02 00:09:18 1  VDV01 Nguyen Van Thanh 00:10:01 00:00:02 00:09:59 2  VDV03 Le Thanh Van 00:10:30 00:00:01 00:10:29 3 |

### J05057 - BẢNG ĐIỂM TUYỂN SINH

Trường Đại học XYZ tuyển sinh theo hình thức xét điểm thi ba môn Toán – Lý – Hóa, trong đó điểm Toán được nhân đôi. Để đơn giản, khu vực tuyển sinh được quy định luôn bởi ba chữ cái đầu tiên trong mã thí sinh. Do rất thích các thí sinh đến từ Khu vực 3 nên trường XYZ tự quy định giá trị điểm ưu tiên Khu vực như trong bảng sau:

![Alt text](./img/J05057_1.png)

Giả sử biết trước điểm chuẩn là 24. Hãy xác định kết quả của từng thí sinh.

**Input**

Dòng đầu tiên ghi số thí sinh (nhỏ hơn 100), thông tin của một thí sinh trên 5 dòng lần lượt là:

- Mã thí sinh
- Họ tên
- Điểm toán
- Điểm lý
- Điểm hóa
 
Các giá trị điểm đều đảm bảo trong phạm vi \[0,10\] và có thể có 1 chữ số phần thập phân.

**Output**

Với mỗi thí sinh (theo đúng thứ tự nhập vào) ghi ra các thông tin:

- Mã thí sinh
- Họ tên
- Điểm ưu tiên (có thể có 1 số phần thập phân)
- Tổng điểm – không tính ưu tiên (có thể có 1 số phần thập phân)
- Trạng thái: TRUNG TUYEN hoac TRUOT (sau khi đã tính cả điểm ưu tiên)
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  KV2A002  Hoang Thanh Tuan  5  6  5  KV2B123  Ly Thi Thu Ha  8  6.5  7 | KV2A002 Hoang Thanh Tuan 1 21 TRUOT  KV2B123 Ly Thi Thu Ha 1 29.5 TRUNG TUYEN |

### J05058 - SẮP XẾP KẾT QUẢ TUYỂN SINH

Trường Đại học XYZ tuyển sinh theo hình thức xét điểm thi ba môn Toán – Lý – Hóa, trong đó điểm Toán được nhân đôi. Để đơn giản, khu vực tuyển sinh được quy định luôn bởi ba chữ cái đầu tiên trong mã thí sinh. Do rất thích các thí sinh đến từ Khu vực 3 nên trường XYZ tự quy định giá trị điểm ưu tiên Khu vực như trong bảng sau:

![Alt text](./img/J05058_1.png)

Giả sử biết trước điểm chuẩn là 24. Hãy xác định kết quả của từng thí sinh và sắp xếp theo điểm xét tuyển giảm dần.

**Input**

Dòng đầu tiên ghi số thí sinh (nhỏ hơn 100), thông tin của một thí sinh trên 5 dòng lần lượt là:

- Mã thí sinh
- Họ tên
- Điểm toán
- Điểm lý
- Điểm hóa
 
Các giá trị điểm đều đảm bảo trong phạm vi \[0,10\] và có thể có 1 chữ số phần thập phân.

**Output**

In ra danh sách đã sắp xếp theo điểm xét tuyển giảm dần, nếu điểm xét tuyển bằng nhau thì sắp xếp theo mã thí sinh (thứ tự từ điển) .

Với mỗi thí sinh ghi ra các thông tin:

- Mã thí sinh
- Họ tên
- Điểm ưu tiên (có thể có 1 số phần thập phân)
- Điểm xét tuyển – có ưu tiên (có thể có 1 số phần thập phân)
- Trạng thái: TRUNG TUYEN hoac TRUOT (sau khi đã tính cả điểm ưu tiên)
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  KV2A002  Hoang Thanh Tuan  5  6  5  KV2B123  Ly Thi Thu Ha  8  6.5  7 | KV2B123 Ly Thi Thu Ha 1 30.5 TRUNG TUYEN  KV2A002 Hoang Thanh Tuan 1 22 TRUOT |

### J05059 - XÁC ĐỊNH DANH SÁCH TRÚNG TUYỂN

Trường Đại học XYZ tuyển sinh theo hình thức xét điểm thi ba môn Toán – Lý – Hóa, trong đó điểm Toán được nhân đôi. Để đơn giản, khu vực tuyển sinh được quy định luôn bởi ba chữ cái đầu tiên trong mã thí sinh. Do rất thích các thí sinh đến từ Khu vực 3 nên trường XYZ tự quy định giá trị điểm ưu tiên Khu vực như trong bảng sau:

![Alt text](./img/J05059_1.png)

Cho trước số chỉ tiêu. Hãy xác định mức điểm chuẩn và kết quả của từng thí sinh sau đó sắp xếp theo điểm xét tuyển giảm dần. Chú ý: tất cả thí sinh bằng điểm chuẩn trở lên đều được coi là trúng tuyển, kể cả khi số thí sinh trúng tuyển nhiều hơn chỉ tiêu.

**Input**

Dòng đầu tiên ghi số thí sinh (nhỏ hơn 100), thông tin của một thí sinh trên 5 dòng lần lượt là:

- Mã thí sinh
- Họ tên
- Điểm toán
- Điểm lý
- Điểm hóa
 
Các giá trị điểm đều đảm bảo trong phạm vi \[0,10\] và có thể có 1 chữ số phần thập phân.

Dòng cuối ghi giá trị số chỉ tiêu.

**Output**

Dòng đầu tiên ghi ra giá trị điểm chuẩn xác định được (có 1 chữ số phần thập phân)

Tiếp theo in ra danh sách đã sắp xếp theo điểm xét tuyển giảm dần, nếu điểm xét tuyển bằng nhau thì sắp xếp theo mã thí sinh (thứ tự từ điển) .

Với mỗi thí sinh ghi ra các thông tin:

- Mã thí sinh
- Họ tên
- Điểm ưu tiên (có thể có 1 số phần thập phân)
- Điểm xét tuyển – có ưu tiên (có thể có 1 số phần thập phân)
- Trạng thái: TRUNG TUYEN hoac TRUOT (sau khi đã tính cả điểm ưu tiên)
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  KV2A002  Hoang Thanh Tuan  5  6  5  KV3B123  Ly Thi Thu Ha  8  6.5  7  1 | 32.0  KV3B123 Ly Thi Thu Ha 2.5 32 TRUNG TUYEN  KV2A002 Hoang Thanh Tuan 1 22 TRUOT |

### J05060 - KẾT QUẢ XÉT TUYỂN

Nghề phụ hồ đang là vua của các nghề. Với mức lương tăng lên chóng mặt, số người thi tuyển để có một vị trí phụ hồ trong các công trường xây dựng đang tăng lên nhanh chóng, bất kể nam hay nữ, già hay trẻ.

Bài thi sát hạch sẽ có ý nghĩa quan trọng để tính lương. Gồm 2 nội dung: thi lý thuyết và thi thực hành. Điểm để xếp loại sẽ là điểm trung bình của hai bài thi đó cộng với điểm thưởng và làm tròn (round) đến hàng đơn vị. (Chú ý nếu tổng lớn hơn 10 thì vẫn chỉ là 10).

Điểm thưởng được tính như sau:

- Nếu không có điểm nào nhỏ hơn 8 thì điểm thưởng = 1
- Nếu không có điểm nào nhỏ hơn 7.5 thì điểm thưởng = 0.5
- Còn lại: không có điểm thưởng.
 
Xếp loại theo quy tắc sau:

- Nhỏ hơn 5: Truot
- Từ 5 đến 6: Trung binh
- Điểm 7: Kha
- Điểm 8: Gioi
- Điểm 9 hoặc 10: Xuat sac
 
Hãy nhập thông tin và lập bảng kết quả xếp loại phụ hồ.

**Input**

Dòng đầu ghi số người thi tuyển (nhỏ hơn 100).

Mỗi người sẽ có thông tin trên 4 dòng gồm:

- Họ tên
- Ngày sinh (đúng định dạng dd/mm/yyyy)
- Điểm lý thuyết
- Điểm thực hành
 
Các giá trị điểm đảm bảo trong phạm vi 10 và có thể có 1 số phần thập phân.

**Output**

Ghi ra danh sách theo đúng thứ tự nhập, các thông tin cách nhau một khoảng trống, lần lượt là:

- Mã thi tuyển (bắt đầu từ PH01)
- Tuổi (chỉ cần tính theo năm sinh)
- Điểm trung bình (đã tính cả điểm thưởng và làm tròn)
- Xếp loại
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Doan Thi Kim  13/03/1982  8  9.5  Dinh Thi Ngoc Ha  03/09/1996  6.5  8  Tran Thanh Mai  12/09/2004  8  9 | PH01 Doan Thi Kim 39 10 Xuat sac  PH02 Dinh Thi Ngoc Ha 25 7 Kha  PH03 Tran Thanh Mai 17 10 Xuat sac |

### J05061 - SẮP XẾP KẾT QUẢ XÉT TUYỂN

Nghề phụ hồ đang là vua của các nghề. Với mức lương tăng lên chóng mặt, số người thi tuyển để có một vị trí phụ hồ trong các công trường xây dựng đang tăng lên nhanh chóng, bất kể nam hay nữ, già hay trẻ.

Bài thi sát hạch sẽ có ý nghĩa quan trọng để tính lương. Gồm 2 nội dung: thi lý thuyết và thi thực hành. Điểm để xếp loại sẽ là điểm trung bình của hai bài thi đó cộng với điểm thưởng và làm tròn (round) đến hàng đơn vị. (Chú ý nếu tổng lớn hơn 10 thì vẫn chỉ là 10).

Điểm thưởng được tính như sau:

- Nếu không có điểm nào nhỏ hơn 8 thì điểm thưởng = 1
- Nếu không có điểm nào nhỏ hơn 7.5 thì điểm thưởng = 0.5
- Còn lại: không có điểm thưởng.
 
Xếp loại theo quy tắc sau:

- Nhỏ hơn 5: Truot
- Từ 5 đến 6: Trung binh
- Điểm 7: Kha
- Điểm 8: Gioi
- Điểm 9 hoặc 10: Xuat sac
 
Hãy nhập thông tin và lập bảng kết quả xếp loại, sau đó sắp xếp theo điểm trung bình giảm dần.

**Input**

Dòng đầu ghi số người thi tuyển (nhỏ hơn 100).

Mỗi người sẽ có thông tin trên 4 dòng gồm:

- Họ tên
- Ngày sinh (đúng định dạng dd/mm/yyyy)
- Điểm lý thuyết
- Điểm thực hành
 
Các giá trị điểm đảm bảo trong phạm vi 10 và có thể có 1 số phần thập phân.

**Output**

Ghi ra danh sách đã được sắp xếp theo điểm trung bình giảm dần (đã tính cả điểm thưởng và đã làm tròn), nếu có cùng điểm trung bình thì sắp xếp theo mã thi tuyển (thứ tự tăng dần).

Các thông tin cách nhau một khoảng trống, lần lượt là:

- Mã thi tuyển (bắt đầu từ PH01)
- Tuổi (chỉ cần tính theo năm sinh)
- Điểm trung bình (đã tính cả điểm thưởng và làm tròn)
- Xếp loại
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Doan Thi Kim  13/03/1982  8  9.5  Dinh Thi Ngoc Ha  03/09/1996  6.5  8  Tran Thanh Mai  12/09/2004  8  9 | PH01 Doan Thi Kim 39 10 Xuat sac  PH03 Tran Thanh Mai 17 10 Xuat sac  PH02 Dinh Thi Ngoc Ha 25 7 Kha |

### J05062 - HỌC BỔNG SINH VIÊN

Học viện Công nghệ Bưu chính Viễn thông xét học bổng khuyến khích học tập cho sinh viên theo các tiêu chí sau:

- Sinh viên có điểm Trung bình chung học kỳ (TBC) &gt;= 3.6 và điểm rèn luyện (RL) &gt;= 90 đạt học bổng xuất sắc.
- Sinh viên có điểm TBC &gt;= 3.2 và điểm RL &gt;= 80 đạt học bổng giỏi.
- Sinh viên có điểm TBC &gt;= 2.5 và điểm RL &gt;= 70 đạt học bổng khá.
- Số lượng sinh viên đạt học bổng được giới hạn theo từng năm dựa vào ngân sách của quỹ học bổng do đó có giới hạn số lượng ưu tiên theo điểm TBC. Trong trường hợp cùng một mức điểm và vượt số lượng thì các sinh viên có cùng mức điểm TBC vẫn được nhận học bổng.
 
Hãy xây dựng chương trình để xét học bổng cho sinh viên học viện.

**Input:**

Dòng đầu tiên đưa vào tổng số sinh viên N và số suất học bổng M.

Những dòng kế tiếp đưa vào N sinh viên. Thông tin mỗi sinh viên gồm 2 dòng, dòng thứ nhất là họ tên của sinh viên (S), dòng thứ hai gồm hai số liên tiếp T là điểm TBC, R là điểm RL.

N, S thỏa mãn ràng buộc: 1≤ T ≤100; 1≤ Length(S)≤100

T, R thỏa mãn ràng buộc: 0.0 &lt;= T &lt;= 4.0, 0 =&lt; R &lt;= 100

**Output:**

Đưa ra kết quả sinh viên có được Học bổng không theo mẫu trong ví dụ, nếu có in ra loại học bổng: XUATSAC, GIOI,KHA, nếu không in ra KHONG.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3 2    Nguyen Van Nam    3.59 75    Tran Hong Ngoc    3.61 90    Do Van An    3.22 90 | Nguyen Van Nam: KHA    Tran Hong Ngoc: XUATSAC    Do Van An: KHONG |

### J05064 - BẢNG THU NHẬP GIÁO VIÊN

Trường phổ thông XYZ tính lương giáo viên theo quy tắc sau:

- Mỗi giáo viên có mã ngạch gồm 4 ký tự trong đó
    - 2 ký tự đầu là chức vụ (HT: Giáo viên kiêm nhiệm Hiệu trưởng, HP: Giáo viên kiêm nhiệm Hiệu phó, GV: Giáo viên thường)
    - 2 ký tự số cuối cùng cho biết hệ số bậc lương (không quá 20)
- Lương cơ bản của mỗi giáo viên cũng có thể khác nhau
- Phụ cấp quy định như sau
    - HT: 2.000.000
    - HP: 900.000
    - GV: 500.000
- Thu nhập được tính bằng lương cơ bản nhân với hệ số bậc lương và cộng thêm phụ cấp.
 
Hãy tính lương cho các giáo viên theo quy tắc trên.

**Input**

Dòng đầu tiên ghi số lượng giáo viên.

Mỗi giáo viên có 3 dòng lần lượt là mã ngạch, họ tên và lương cơ bản.

*Chú ý: chỉ cho phép có tối đa 1 Hiệu trưởng và 2 Hiệu phó, ưu tiên theo thứ tự nhập. Tức là từ người thứ 2 có mã HT hoặc người thứ 3 có mã HP trở lên sẽ không được đưa vào danh sách khi in ra.*

**Ouput**

Ghi ra danh sách giáo viên theo đúng thứ tự nhập, với lần lượt các thông tin: mã ngạch, họ tên, bậc lương, phụ cấp, thu nhập.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  GV01  Nguyen Kim Loan  1420000  HT05  Hoang Thanh Tuan  1780000  GV02  Tran Binh Nguyen  1468000 | GV01 Nguyen Kim Loan 1 500000 1920000  HT05 Hoang Thanh Tuan 5 2000000 10900000  GV02 Tran Binh Nguyen 2 500000 3436000 |

### J05065 - LIỆT KÊ NHÂN VIÊN THEO NHÓM

Công ty ABC tổ chức mã nhân viên gồm 7 ký tự trong đó:

- 2 ký tự đầu tiên là chức vụ (GD: Giám đốc, TP: Trưởng phòng, PP: Phó phòng, NV: Nhân viên).
- 2 chữ số tiếp theo là hệ số lương (không quá 15)
- 3 chữ số cuối mà số hiệu nhân viên
 
Công ty chỉ có 1 giám đốc và không quá 3 trưởng phòng, 3 phó phòng. Quá trình nhập dữ liệu có thể bị nhầm nên từ người thứ 2 trở lên có mã GD hoặc người thứ 4 trở lên có mã TP, PP thì được hiểu là nhân viên thường (coi như mã chính xác bắt đầu bằng NV).

Hãy viết chương trình nhập danh sách nhân viên và liệt kê theo nhóm chức vụ được yêu cầu. Cần sắp xếp danh sách theo bậc lương giảm dần. Trong trường hợp bậc lương bằng nhau thì sắp xếp theo số hiệu tăng dần

**Input**

Dòng đầu tiên là số nhân viên (không quá 50)

Mỗi nhân viên chỉ có 1 dòng gồm mã nhân viên sau đó đến họ tên.

Sau đó là một dòng ghi số m là số truy vấn (không quá 3).

Tiếp theo là m dòng, mỗi dòng ghi ra một chức vụ cần truy vấn.

**Output**

Với mỗi truy vấn, liệt kê danh sách nhân viên của nhóm chức vụ đó, đã sắp xếp theo tiêu chí trong đề bài. Hết một nhóm thì thêm một dòng trống.

Thông tin 1 nhân viên bao gồm: tên, mã chức vụ, số hiệu, bậc lương.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 6  GD08001 Nguyen Kim Loan  TP05002 Hoang Thanh Tuan  TP05001 Tran Binh Nguyen  PP06002 Phan Trung Tuan  PP06001 Tran Quoc Huy  NV04003 Vo Van Lan  2  TP  PP | Tran Binh Nguyen TP 001 05  Hoang Thanh Tuan TP 002 05  Tran Quoc Huy PP 001 06  Phan Trung Tuan PP 002 06 |

### J05066 - TÌM KIẾM NHÂN VIÊN THEO TÊN

Công ty ABC tổ chức mã nhân viên gồm 7 ký tự trong đó:

- 2 ký tự đầu tiên là chức vụ (GD: Giám đốc, TP: Trưởng phòng, PP: Phó phòng, NV: Nhân viên).
- 2 chữ số tiếp theo là hệ số lương (không quá 15)
- 3 chữ số cuối mà số hiệu nhân viên
 
Công ty chỉ có 1 giám đốc và không quá 3 trưởng phòng, 3 phó phòng. Quá trình nhập dữ liệu có thể bị nhầm nên từ người thứ 2 trở lên có mã GD hoặc người thứ 4 trở lên có mã TP, PP thì được hiểu là nhân viên thường (coi như mã chính xác bắt đầu bằng NV).

Hãy viết chương trình nhập danh sách nhân viên, sau đó tìm kiếm các nhân viên có tên gần đúng với từ khóa.

*Tìm kiến gần đúng được hiểu là trong xâu ký tự họ tên tồn tại từ khóa cần tìm, không phân biệt chữ hoa, chữ thường.*

Cần sắp xếp danh sách tìm kiếm theo bậc lương giảm dần. Trong trường hợp bậc lương bằng nhau thì sắp xếp theo số hiệu tăng dần.

**Input**

Dòng đầu tiên là số nhân viên (không quá 50)

Mỗi nhân viên chỉ có 1 dòng gồm mã nhân viên sau đó đến họ tên.

Sau đó là một dòng ghi số m là số truy vấn (không quá 3).

Tiếp theo là m dòng, mỗi dòng ghi ra một từ khóa.

**Output**

Với mỗi truy vấn, liệt kê danh sách nhân viên tìm thấy theo từ khóa đó, đã sắp xếp theo tiêu chí trong đề bài. Hết một nhóm thì thêm một dòng trống.

Thông tin 1 nhân viên bao gồm: tên, mã chức vụ, số hiệu, bậc lương.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 6  GD08001 Nguyen Kim Loan  TP05002 Hoang Thanh Tuan  TP05001 Tran Binh Nguyen  PP06002 Phan Trung Tuan  PP06001 Tran Quoc Huy  NV04003 Vo Van Lan  2  OA  aN | Nguyen Kim Loan GD 001 08  Hoang Thanh Tuan TP 002 05  Nguyen Kim Loan GD 001 08  Tran Quoc Huy PP 001 06  Phan Trung Tuan PP 002 06  Tran Binh Nguyen TP 001 05  Hoang Thanh Tuan TP 002 05  Vo Van Lan NV 003 04 |

### J05067 - QUẢN LÝ KHO XĂNG DẦU

Một kho xăng dầu nhập khẩu (hoặc đặt hàng trong nước) 3 sản phẩm chính là Xăng, Dầu và Nhớt. Ký tự đầu tiên trong mã đơn hàng sẽ cho biết loại mặt hàng. Đơn giá bán ra và thuế được cho như trong bảng sau:

![Alt text](./img/J05067_1.png)

Hai chữ cái cuối cùng của mã đơn hàng sẽ cho biết hãng sản xuất như trong bảng:

![Alt text](./img/J05067_2.png)

Riêng mặt hàng sản xuất Trong Nước sẽ có hai chữ cái cuối cùng là TN và không bị tính thuế. Trong trường hợp đó, khi in thì hãng là Trong Nuoc

Cho biết đơn giá và số lượng, hãy tính thành tiền cho mỗi đơn hàng.

**Input**

Dòng đầu ghi số đơn hàng (không quá 50).

Mỗi đơn hàng chỉ có một dòng ghi 2 thông tin: mã đơn hàng và số lượng.

Số lượng không quá 106.

**Output**

Ghi ra danh sách các đơn hàng theo đúng thứ tự nhập vào, gồm lần lượt các thông tin

- Mã đơn hàng
- Hãng sản xuất
- Đơn giá
- Thuế
- Thành tiền
 
Dữ liệu vào đảm bảo tất cả các giá trị đều là số nguyên. Các thông tin viết ra cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  N89BP 4500  D00BP 3500  X92SH 2600 | N89BP British Petro 9700 873000 44523000  D00BP British Petro 11200 1372000 40572000  X92SH Shell 128000 9984000 342784000 |

### J05068 - SẮP XẾP BẢNG GIÁ XĂNG DẦU

Một kho xăng dầu nhập khẩu hoặc đặt hàng trong nước 3 sản phẩm chính là Xăng, Dầu và Nhớt. Ký tự đầu tiên trong mã đơn hàng sẽ cho biết loại mặt hàng. Đơn giá bán ra và thuế nhập khẩu được cho như trong bảng sau:

![Alt text](./img/J05068_1.png)

Hai chữ cái cuối cùng của mã đơn hàng sẽ cho biết hãng sản xuất như trong bảng:

![Alt text](./img/J05068_2.png)

Riêng mặt hàng sản xuất Trong Nước sẽ có hai chữ cái cuối cùng là TN và không bị tính thuế. Khi in ra hang se ghi la Trong Nuoc

Cho biết đơn giá và số lượng, hãy tính thành tiền cho mỗi đơn hàng, sau đó sắp xếp theo thành tiền giảm dần.

**Input**

Dòng đầu ghi số đơn hàng (không quá 50).

Mỗi đơn hàng chỉ có một dòng ghi 2 thông tin: mã đơn hàng và số lượng.

Số lượng không quá 106.

**Output**

Ghi ra danh sách các đơn hàng đã sắp xếp theo tiêu chí của đề bài, gồm lần lượt các thông tin

- Mã đơn hàng
- Hãng sản xuất
- Đơn giá
- Thuế
- Thành tiền
 
Dữ liệu vào đảm bảo tất cả các giá trị đều là số nguyên. Các thông tin viết ra cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  N89BP 4500  D00BP 3500  X92SH 2600 | X92SH Shell 128000 9984000 342784000  N89BP British Petro 9700 873000 44523000  D00BP British Petro 11200 1372000 40572000 |

### J05069 - CÂU LẠC BỘ BÓNG ĐÁ - 1

Giả sử bạn có thông tin để tính toán xem doanh thu của mỗi CLB bóng đá trong một trận đấu là bao nhiêu (chỉ tính tiền bán vé).

Mỗi CLB có 3 thông tin gồm:

- - Mã CLB: gồm hai chữ cái in hoa
    - Tên CLB: độ dài không quá 80
    - Giá vé
 
Thông tin về một trận đấu chỉ có hai thông tin:

- - Mã trận đấu: trong đó ký tự đầu tiên là mã nước, hai ký tự tiếp theo là mã CLB, chữ số cuối cùng là thứ tự trận đấu. Trong bài toán này ta chỉ quan tâm đến mã CLB.
    - Số cổ động viên mua vé vào sân
 
Hãy tính doanh thu cho từng trận.

**Input**

Dòng đầu ghi số đội bóng Mỗi đội viết trên ba dòng lần lượt là mã, tên, giá vé.

Tiếp theo là một dòng ghi số lượng trận đấu. Mỗi trận chỉ viết trên một dòng với hai thông tin: mã trận và số cổ động viên.

**Output**

Ghi ra danh sách trận đấu theo thứ tự nhập gồm các thông tin: mã trận, tên đội, doanh thu. Các thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  AC  AC Milan  12  MU  Manchester United  10  2  IAC1 80000  EMU2 60000 | IAC1 AC Milan 960000  EMU2 Manchester United 600000 |

### J05070 - CÂU LẠC BỘ BÓNG ĐÁ - 2

Giả sử bạn có thông tin để tính toán xem doanh thu của mỗi CLB bóng đá trong một trận đấu là bao nhiêu (chỉ tính tiền bán vé).

Mỗi CLB có 3 thông tin gồm:

- - Mã CLB: gồm hai chữ cái in hoa
    - Tên CLB: độ dài không quá 80
    - Giá vé
 
Thông tin về một trận đấu chỉ có hai thông tin:

- - Mã trận đấu: trong đó ký tự đầu tiên là mã nước, hai ký tự tiếp theo là mã CLB, chữ số cuối cùng là thứ tự trận đấu. Trong bài toán này ta chỉ quan tâm đến mã CLB.
    - Số cổ động viên mua vé vào sân
 
Hãy tính doanh thu cho từng trận.

**Input**

Dòng đầu ghi số đội bóng Mỗi đội viết trên ba dòng lần lượt là mã, tên, giá vé.

Tiếp theo là một dòng ghi số lượng trận đấu. Mỗi trận chỉ viết trên một dòng với hai thông tin: mã trận và số cổ động viên.

**Output**

Ghi ra danh sách trận đấu theo thứ tự doanh thu giảm dần, nếu doanh thu bằng nhau thì sắp xếp theo tên đội (thứ tự từ điển).

Các thông tin về một trận đấu được ghi cách nhau một khoảng trống gồm: mã trận, tên đội, doanh thu.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  AC  AC Milan  12  MU  Manchester United  10  2  IAC1 80000  EMU2 60000 | IAC1 AC Milan 960000  EMU2 Manchester United 600000 |

### J05071 - TÍNH CƯỚC ĐIỆN THOẠI CỐ ĐỊNH - 1

Khi điện thoại di động còn chưa phổ biến, điện thoại cố định là phương tiện liên lạc chính. Mỗi cuộc gọi sẽ được tính cước dựa trên số máy gọi đến. Trong đó nếu gọi nội mạng thì cước rất rẻ so với gọi liên tỉnh, và mỗi tỉnh sẽ có mức cước khác nhau.

Mỗi tỉnh thành phố sẽ có 3 thông tin gồm:

- - Mã vùng
    - Tên
    - Giá cước
 
Mỗi cuộc gọi có các thông tin:

- - Thuê bao gọi đến
    - Thời điểm bắt đầu cuộc gọi (hh:mm)
    - Thời điểm kết thúc cuộc gọi (hh:mm)
 
Các cuộc gọi có mã số 0 ở đầu là liên tỉnh, khi đó chữ số thứ 2 và thứ 3 sẽ tương ứng với mã vùng của số gọi đến. Trong trường hợp không có số 0 ở đầu thì là cuộc gọi nội mạng. Cước nội mạng được tính riêng là 800 VNĐ/phút. Tuy nhiên trong đợt khuyến mại này thì số phút gọi nội mạng còn được chia 3 rồi làm tròn lên (ví dụ 8 phút thì sẽ chỉ tính tiền 3 phút).

Hãy viết chương trình tính cước các cuộc gọi.

**Input**

Dòng đầu ghi số tỉnh – thành phố. Tiếp theo, thông tin mỗi tỉnh thành phố sẽ có 3 dòng gồm mã vùng, tên tỉnh và giá cước.

Tiếp theo là một dòng ghi số lượng cuộc gọi.

Mỗi cuộc gọi ghi thông tin trên 1 dòng gồm 3 cụm: số thuê bao gọi đến, giờ bắt đầu, giờ kết thúc. Giả sử không có cuộc gọi nào qua thời điểm 0 giờ đêm, giờ kết thúc luôn lớn hơn giờ bắt đầu.

**Output**

Ghi ra lần lượt thông tin mỗi cuộc gọi (theo thứ tự nhập) gồm:

- - Số thuê bao gọi đến
    - Tỉnh – thành phố tương ứng (nếu nội mạng thì ghi *Noi mang*)
    - Số phút gọi (đã tính khuyến mại cho gọi nội mạng)
    - Giá cước phải trả
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  53  Da Nang  3000  64  Vung Tau  1000  3  064-824531 11:20 11:22  8293567 09:07 09:15  053-823532 12:00 12:05 | 064-824531 Vung Tau 2 2000  8293567 Noi mang 3 2400  053-823532 Da Nang 5 15000 |

### J05072 - TÍNH CƯỚC ĐIỆN THOẠI CỐ ĐỊNH - 2

Khi điện thoại di động còn chưa phổ biến, điện thoại cố định là phương tiện liên lạc chính. Mỗi cuộc gọi sẽ được tính cước dựa trên số máy gọi đến. Trong đó nếu gọi nội mạng thì cước rất rẻ so với gọi liên tỉnh, và mỗi tỉnh sẽ có mức cước khác nhau.

Mỗi tỉnh thành phố sẽ có 3 thông tin gồm:

- - Mã vùng
    - Tên
    - Giá cước
 
Mỗi cuộc gọi có các thông tin:

- - Thuê bao gọi đến
    - Thời điểm bắt đầu cuộc gọi (hh:mm)
    - Thời điểm kết thúc cuộc gọi (hh:mm)
 
Các cuộc gọi có mã số 0 ở đầu là liên tỉnh, khi đó chữ số thứ 2 và thứ 3 sẽ tương ứng với mã vùng của số gọi đến. Trong trường hợp không có số 0 ở đầu thì là cuộc gọi nội mạng. Cước nội mạng được tính riêng là 800 VNĐ/phút. Tuy nhiên trong đợt khuyến mại này thì số phút gọi nội mạng còn được chia 3 rồi làm tròn lên (ví dụ 8 phút thì sẽ chỉ tính tiền 3 phút).

Hãy viết chương trình tính cước các cuộc gọi.

**Input**

Dòng đầu ghi số tỉnh – thành phố. Tiếp theo, thông tin mỗi tỉnh thành phố sẽ có 3 dòng gồm mã vùng, tên tỉnh và giá cước.

Tiếp theo là một dòng ghi số lượng cuộc gọi.

Mỗi cuộc gọi ghi thông tin trên 1 dòng gồm 3 cụm: số thuê bao gọi đến, giờ bắt đầu, giờ kết thúc. Giả sử không có cuộc gọi nào qua thời điểm 0 giờ đêm, giờ kết thúc luôn lớn hơn giờ bắt đầu.

**Output**

Ghi ra lần lượt thông tin mỗi cuộc gọi đã sắp xếp theo giá cước giảm dần. Input đảm bảo không có 2 cuộc gọi nào có giá cước bằng nhau. Các thông tin cần liệt kê gồm:

- - Số thuê bao gọi đến
    - Tỉnh – thành phố tương ứng (nếu nội mạng thì ghi *Noi mang*)
    - Số phút gọi (đã tính khuyến mại cho gọi nội mạng)
    - Giá cước phải trả
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  53  Da Nang  3000  64  Vung Tau  1000  3  064-824531 11:20 11:22  8293567 09:07 09:15  053-823532 12:00 12:05 | 053-823532 Da Nang 5 15000  8293567 Noi mang 3 2400  064-824531 Vung Tau 2 2000 |

### J05073 - TÍNH TOÁN GIÁ BÁN

Một cửa hàng điện máy nhập hàng nguyên chiếc để bán. Các chi phí liên quan gồm tiền hàng (số lượng \* đơn giá), thuế nhập khẩu, phí vận chuyển. Trong đó thuế nhập khẩu và phí vận chuyển được tính theo bảng sau (giả sử chữ cái đầu tiên trong mã hàng sẽ quyết định mức thuế và phí vận chuyển).

![Alt text](./img/J05073_1.png)

Chữ cái cuối cùng của mã hàng là C hoặc K (có chứng từ đầy đủ hoặc không). Mặt hàng nào có chữ cuối cùng là C thì được giảm thêm 5% thuế so với mức trong bảng trên.

Hãy tính giá bán từng sản phẩm.

Biết rằng sau khi tính tổng chi phí gồm tiền hàng với thuế và phí vận chuyển, cửa hàng sẽ tính thêm 20% lợi nhuận trên mỗi đơn hàng. Sau đó chia cho số lượng và làm tròn đến 2 số phần thập phân.

**Input**

Dòng đầu ghi số đơn hàng. Mỗi đơn hàng ghi trên một dòng gồm mã, đơn giá, số lượng.

**Output**

Ghi ra danh sách đơn hàng (theo thứ tự nhập) gồm mã đơn hàng và giá bán mỗi mặt hàng (đã làm tròn đến 2 số phần thập phân).

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  TTVC 400 300  CCAK 200 200 | TTVC 631.44  CCAK 271.20 |

### J05074 - ĐIỂM DANH - 1

Lớp học phần môn XYZ của trường ABC có không quá 100 sinh viên. Danh sách sinh viên gồm các thông tin: mã sinh viên, họ tên, lớp. Môn học có 10 buổi. Dữ liệu điểm danh với mỗi sinh viên được cho bởi một xâu ký tự gồm 10 ký tự trong đó: x là có mặt, m là đến muộn, v là vắng.

Với điểm chuyên cần tối đa là 10. Giả sử mỗi buổi vắng bị trừ 2 điểm, mỗi buổi đến muộn bị trừ 1 điểm. Hãy tính điểm chuyên cần cho mỗi sinh viên (tất nhiên nếu tính ra điểm âm thì ghi vào bảng điểm vẫn là 0).

Nếu điểm bằng 0 thì in thêm ghi chú KDDK (tức là không đủ điều kiện dự thi hết môn).

**Input**

Dòng đầu ghi số n là số sinh viên. Mỗi sinh viên ghi trên 3 dòng lần lượt là mã sinh viên, họ tên, lớp.

Tiếp theo là n dòng ghi dữ liệu điểm danh. Mỗi dòng gồm mã sinh viên, sau đó là một khoảng trống rồi đến xâu ký tự điểm danh có đúng 10 chữ cái.

**Output**

Ghi ra danh sách điểm chuyên cần (theo đúng thứ tự ban đầu) gồm các thông tin:

- Mã sinh viên
- Họ và tên
- Lớp
- Điểm chuyên cần
- Ghi chú (nếu có)
 
Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  B19DCCN999  Le Cong Minh  D19CQAT02-B  B19DCCN998  Tran Truong Giang  D19CQAT02-B  B19DCCN997  Nguyen Tuan Anh  D19CQCN04-B  B19DCCN998 xxxmxmmvmx  B19DCCN997 xmxmxxxvxx  B19DCCN999 xvxmxmmvvm | B19DCCN999 Le Cong Minh D19CQAT02-B 0 KDDK  B19DCCN998 Tran Truong Giang D19CQAT02-B 4  B19DCCN997 Nguyen Tuan Anh D19CQCN04-B 6 |

### J05075 - ĐIỂM DANH - 2

Lớp học phần môn XYZ của trường ABC có không quá 100 sinh viên. Danh sách sinh viên gồm các thông tin: mã sinh viên, họ tên, lớp. Môn học có 10 buổi. Dữ liệu điểm danh với mỗi sinh viên được cho bởi một xâu ký tự gồm 10 ký tự trong đó: x là có mặt, m là đến muộn, v là vắng.

Với điểm chuyên cần tối đa là 10. Giả sử mỗi buổi vắng bị trừ 2 điểm, mỗi buổi đến muộn bị trừ 1 điểm. Hãy tính điểm chuyên cần cho mỗi sinh viên (tất nhiên nếu tính ra điểm âm thì ghi vào bảng điểm vẫn là 0).

Nếu điểm bằng 0 thì in thêm ghi chú KDDK (tức là không đủ điều kiện dự thi hết môn).

Chỉ ghi ra danh sách sinh viên theo lớp được yêu cầu.

**Input**

Dòng đầu ghi số n là số sinh viên. Mỗi sinh viên ghi trên 3 dòng lần lượt là mã sinh viên, họ tên, lớp.

Tiếp theo là n dòng ghi dữ liệu điểm danh. Mỗi dòng gồm mã sinh viên, sau đó là một khoảng trống rồi đến xâu ký tự điểm danh có đúng 10 chữ cái.

Dòng cuối cùng ghi mã lớp cần liệt kê danh sách

**Output**

Ghi ra danh sách điểm chuyên cần của sinh viên trong lớp (theo đúng thứ tự ban đầu) gồm các thông tin:

- Mã sinh viên
- Họ và tên
- Lớp
- Điểm chuyên cần
- Ghi chú (nếu có)
 
Mỗi thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  B19DCCN999  Le Cong Minh  D19CQAT02-B  B19DCCN998  Tran Truong Giang  D19CQAT02-B  B19DCCN997  Nguyen Tuan Anh  D19CQCN04-B  B19DCCN998 xxxmxmmvmx  B19DCCN997 xmxmxxxvxx  B19DCCN999 xvxmxmmvvm  D19CQAT02-B | B19DCCN999 Le Cong Minh D19CQAT02-B 0 KDDK  B19DCCN998 Tran Truong Giang D19CQAT02-B 4 |

### J05076 - NHẬP XUẤT HÀNG

Cửa hàng điện máy muốn thống kê tính toán các giao dịch nhập, xuất hàng trong kỳ. Mỗi mặt hàng có mã hàng, tên hàng và xếp loại. Trong đó xếp loại mặt hàng do cửa hàng tự đặt ra khi nhập hàng với ba giá trị A, B, C tương ứng với mức lãi suất kỳ vọng khi xuất hàng lần lượt là 8%, 5% và 2%.

Hãy tính tổng giá trị nhập và xuất của mỗi mặt hàng trong kỳ.

Biết rằng có thể có mặt hàng xuất hiện nhiều hơn một lần vì được nhập vào các thời điểm khác nhau, khi đó có thể đơn giá nhập cũng khác nhau và vẫn được thống kê thành các dòng độc lập, không cần cộng dồn.

Đơn giá các mặt hàng điện máy (tính bằng USD) thường cao và là số tròn chục nên khi tính tổng giá trị xuất với tỉ lệ lợi nhuận kỳ vọng thì cũng sẽ vẫn nhận được các giá trị nguyên.

**Input:**

Dòng đầu ghi số n là số mặt hàng. Mỗi mặt hàng ghi trên 3 dòng gồm: mã, tên và xếp loại.

Tiếp theo là một dòng ghi số m là số dòng thống kê trong bảng.

Mỗi dòng thống kê gồm các thông tin: mã hàng, số lượng nhập, đơn giá nhập, số lượng xuất. Với các giá trị đều nguyên dương và số lượng xuất đảm bảo không vượt quá số lượng nhập.

**Output:**

Ghi ra đúng m dòng theo đúng thứ tự nhập gồm các thông tin:

- Mã hàng
- Tên hàng
- Tổng trị giá nhập
- Tổng trị giá xuất
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  A001  Tu lanh  A  P002  May giat  B  2  A001 500 100 300  P002 1000 1000 500 | A001 Tu lanh 50000 32400  P002 May giat 1000000 525000 |

### J05077 - TÍNH LƯƠNG

Công ty XYZ mỗi năm đều cập nhật hồ sơ và gán lại mã cho nhân viên (có đúng 5 ký tự) theo quy tắc sau:

- Ký tự đầu tiên là phân loại nhân viên, có 4 nhóm là A, B, C, D
- Hai chữ số tiếp theo mô tả số năm công tác
- Hai ký tự cuối là mã phòng ban.
 
Dựa trên loại nhân viên và số năm công tác, hệ số nhân để tính lương được cho trong bảng sau:

![Alt text](./img/J05077_1.png)

Mỗi nhân viên theo hợp đồng sẽ có một giá trị lương cơ bản có thể rất khác nhau. Lương tháng được tính bằng tích của lương cơ bản với số ngày công và hệ số nhân.

Cho trước danh sách phòng ban, gồm mã phòng và tên phòng. Cho trước các thông tin nhân viên gồm mã, tên, lương cơ bản (tính theo ngày – đơn vị nghìn VNĐ) và số ngày công. Hãy tính toán và in ra bảng lương nhân viên trong tháng.

**Input**

Dòng đầu ghi số phòng ban, mỗi phòng ban viết trên một dòng gồm mã phòng và tên phòng.

Tiếp theo là một dòng ghi số nhân viên, mỗi nhân viên ghi trên 4 dòng gồm mã, tên, lương cơ bản (tính theo ngày), số ngày công.

**Output**

Lập bảng lương của nhân viên theo đúng thứ tự nhập. Mỗi nhân viên cần ghi ra các thông tin sau đây trên một dòng:

- Mã nhân viên
- Tên nhân viên
- Phòng ban
- Lương tháng
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  HC Hanh chinh  KH Ke hoach Dau tu  2  C06HC  Tran Binh Minh  65  25  D03KH  Le Hoa Binh  59  24 | C06HC Tran Binh Minh Hanh chinh 16250000  D03KH Le Hoa Binh Ke hoach Dau tu 11328000 |

### J05078 - BẢNG LƯƠNG THEO PHÒNG BAN

Công ty XYZ mỗi năm đều cập nhật hồ sơ và gán lại mã cho nhân viên (có đúng 5 ký tự) theo quy tắc sau:

- Ký tự đầu tiên là phân loại nhân viên, có 4 loại là A, B, C, D
- Hai chữ số tiếp theo mô tả số năm công tác
- Hai ký tự cuối là mã phòng ban.
 
Dựa trên loại nhân viên và số năm công tác, hệ số nhân để tính lương được cho trong bảng sau:

![Alt text](./img/J05078_1.png)

Mỗi nhân viên theo hợp đồng sẽ có một giá trị lương cơ bản có thể rất khác nhau. Lương tháng được tính bằng tích của lương cơ bản với số ngày công và hệ số nhân.

Cho trước danh sách phòng ban, gồm mã phòng và tên phòng. Cho trước các thông tin nhân viên gồm mã, tên, lương cơ bản (tính theo ngày – đơn vị nghìn VNĐ) và số ngày công. Hãy tính toán và in ra bảng lương nhân viên cho một phòng ban.

**Input**

Dòng đầu ghi số phòng ban, mỗi phòng ban viết trên một dòng gồm mã phòng và tên phòng.

Tiếp theo là một dòng ghi số nhân viên, mỗi nhân viên ghi trên 4 dòng gồm mã, tên, lương cơ bản (tính theo ngày), số ngày công.

Tiếp theo là một dòng ghi mã phòng ban cần thống kê bảng lương.

**Output**

Lập bảng lương của nhân viên trong phòng ban đó theo đúng thứ tự nhập. Mỗi nhân viên cần ghi ra các thông tin sau đây trên một dòng:

- Mã nhân viên
- Tên nhân viên
- Lương tháng
 
Mẫu bảng lương cần trình bày như trong ví dụ dưới đây.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  HC Hanh chinh  KH Ke hoach Dau tu  2  C06HC  Tran Binh Minh  65  25  D03KH  Le Hoa Binh  59  24  KH | Bang luong phong Ke hoach Dau tu:  D03KH Le Hoa Binh 11328000 |

### J05079 - LỚP HỌC PHẦN – 1

Một lớp học phần tại Học viện Công nghệ Bưu chính Viễn thông sẽ gồm các thông tin:

- Mã môn học
- Tên môn học
- Nhóm lớp (thường được đánh số từ 01, tối đa mỗi môn không quá 40 nhóm)
- Tên giảng viên
 
Hãy nhập thông tin danh sách các lớp học phần của học kỳ này và liệt kê danh sách các lớp theo môn học.

**Input**

Dòng đầu ghi số n là số lớp học phần.

Mỗi lớp học phần ghi trên 4 dòng lần lượt là mã, tên, nhóm, tên giảng viên.

Tiếp theo là một dòng ghi số m là số môn cần liệt kê danh sách

Sau đó là m dòng, mỗi dòng ghi một mã môn học.

**Output**

Với mỗi môn học, ghi ra danh sách lớp học phần theo thứ tự nhóm từ nhỏ đến lớn. Chỉ cần liệt kê hai thông tin là nhóm và tên giảng viên.

Xem ví dụ để hiểu rõ hơn cách hiển thị danh sách.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  THCS2D20  Tin hoc co so 2 - D20  01  Nguyen Binh An  CPPD20  Ngon ngu lap trinh C++ - D20  01  Le Van Cong  THCS2D20  Tin hoc co so 2 - D20  02  Nguyen Trung Binh  LTHDTD19  Lap trinh huong doi tuong - D19  01  Nguyen Binh An  1  THCS2D20 | Danh sach nhom lop mon Tin hoc co so 2 - D20:  01 Nguyen Binh An  02 Nguyen Trung Binh |

### J05080 - LỚP HỌC PHẦN – 2

Một lớp học phần tại Học viện Công nghệ Bưu chính Viễn thông sẽ gồm các thông tin:

- Mã môn học
- Tên môn học
- Nhóm lớp (thường được đánh số từ 01, tối đa mỗi môn không quá 40 nhóm)
- Tên giảng viên
 
Hãy nhập thông tin danh sách các lớp học phần của học kỳ này và liệt kê danh sách các lớp theo giảng viên.

**Input**

Dòng đầu ghi số n là số lớp học phần.

Mỗi lớp học phần ghi trên 4 dòng lần lượt là mã, tên, nhóm, tên giảng viên.

Tiếp theo là một dòng ghi số m là số giảng viên liệt kê danh sách

Sau đó là m dòng, mỗi dòng ghi tên 1 giảng viên.

**Output**

Với mỗi giảng viên, ghi ra danh sách lớp học phần theo thứ tự mã môn học, nếu cùng môn học thì liệt kê theo thứ tự nhóm từ nhỏ đến lớn. Cần liệt kê các thông tin: mã môn, tên môn, nhóm.

Xem ví dụ để hiểu rõ hơn cách hiển thị danh sách.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  THCS2D20  Tin hoc co so 2 - D20  01  Nguyen Binh An  CPPD20  Ngon ngu lap trinh C++ - D20  01  Le Van Cong  THCS2D20  Tin hoc co so 2 - D20  02  Nguyen Trung Binh  LTHDTD19  Lap trinh huong doi tuong - D19  01  Nguyen Binh An  1  Nguyen Binh An | Danh sach cho giang vien Nguyen Binh An:  LTHDTD19 Lap trinh huong doi tuong - D19 01  THCS2D20 Tin hoc co so 2 - D20 01 |

### J05081 - DANH SÁCH MẶT HÀNG

Bài toán quản lý danh sách mặt hàng trong đó mỗi mặt hàng sẽ có các thông tin:

- Mã mặt hàng: tự động tăng, tính từ MH001
- Tên mặt hàng: xâu ký tự độ dài không quá 100
- Đơn vị tính: xâu ký tự độ dài không quá 10
- Giá mua: số nguyên dương không quá 7 chữ số
- Giá bán: số nguyên dương không quá 7 chữ số
 
Viết chương trình nhập danh sách mặt hàng, sắp xếp theo lợi nhuận (giá bán trừ đi giá mua) giảm dần. Nếu lợi nhuận bằng nhau thì in ra theo thứ tự mã tăng dần.

**Input**

Dòng đầu ghi số M là số mặt hàng (không quá 40).

Tiếp theo là thông tin của M mặt hàng, mỗi mặt hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

**Output**

Ghi ra danh sách mặt hàng có đầy đủ thông tin ở trên và lợi nhuận tính được (mỗi thông tin cách nhau một khoảng trống)

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2    Ao phong tre em    Cai    25000    41000    Ao khoac nam    Cai    240000    515000 | MH002 Ao khoac nam Cai 240000 515000 275000    MH001 Ao phong tre em Cai 25000 41000 16000 |

### J05082 - DANH SÁCH KHÁCH HÀNG

Bài toán quản lý danh sách khách hàng, trong đó mỗi Khách hàng có các thông tin:

- Mã khách hàng: tự động tăng, tính từ KH001
- Tên khách hàng: xâu ký tự độ dài không quá 50, cần đưa về dạng chuẩn
- Giới tính: Nam hoặc Nu
- Ngày sinh: cần đưa về dạng chuẩn dd/mm/yyyy
- Địa chỉ: xâu ký tự độ dài không quá 100
 
Viết chương trình nhập danh sách khách hàng, sắp xếp theo ngày sinh từ già nhất đến trẻ nhất. Không có hai khách hàng nào cùng ngày sinh.

**Input**

Dòng đầu ghi số N là số khách hàng (không quá 20).

Tiếp theo là thông tin của N khách hàng, mỗi khách hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

**Output**

Danh sách khách hàng với đầy đủ các thông tin liệt kê ở trên, trong đó tên và ngày sinh đã được chuẩn hóa.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2    nGuyen VAN nAm    Nam    12/12/1997    Mo Lao-Ha Dong-Ha Noi    TRan vAn biNh    Nam    14/11/1995    Phung Khoang-Nam Tu Liem-Ha Noi | KH002 Tran Van Binh Nam Phung Khoang-Nam Tu Liem-Ha Noi 14/11/1995    KH001 Nguyen Van Nam Nam Mo Lao-Ha Dong-Ha Noi 12/12/1997 |

### J07038 - DANH SÁCH THỰC TẬP - 3

Để chuẩn bị cho đợt thực tập tốt nghiệp của sinh viên năm cuối, Khoa CNTT1 trao đổi với các doanh nghiệp đối tác và chốt số lượng sinh viên có thể nhận thực tập.

Mỗi doanh nghiệp được mô tả gồm ba thông tin: mã doanh nghiệp, tên doanh nghiệp, số sinh viên có thể nhận.

Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100, có thể chưa chuẩn
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 30)
 
Dữ liệu đăng ký thực tập sẽ được nhập chỉ với hai thông tin: mã sinh viên, mã doanh nghiệp.

Hãy viết chương trình nhập danh sách thực tập và hiển thị danh sách thực tập theo doanh nghiệp.

Chú ý: các doanh nghiệp sẽ ưu tiên lấy sinh viên theo thứ tự mã sinh viên (thứ tự từ điển). Giả sử số sinh viên tối đa có thể nhận là N thì từ sinh viên thứ N+1 trở đi theo danh sách đã sắp xếp theo mã sinh viên thì sẽ không được nhận.

**Input – 3 file văn bản**

**SINHVIEN.in**

Dòng đầu ghi số sinh viên (không quá 1000)

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

**DN.in**

Dòng đầu ghi số doanh nghiệp.

Mỗi doanh nghiệp ghi trên 3 dòng: Mã doanh nghiệp, Tên doanh nghiệp, Số sinh viên có thể nhận.

**THUCTAP.in**

Dòng đầu ghi số N là số lượng đăng ký

Tiếp theo là N dòng, mỗi dòng có hai thông tin là mã sinh viên và mã doanh nghiệp.

Tiếp theo là một dòng ghi số M là số doanh nghiệp cần liệt kê danh sách.

Sau đó là M dòng mỗi dòng ghi 1 mã doanh nghiệp

**Output**

Ghi ra danh sách thực tập của từng doanh nghiệp theo mẫu trong ví dụ. Mỗi sinh viên cần liệt kê mã, tên, lớp, danh sách được sắp xếp theo mã sinh viên tăng dần.

**Ví dụ**

 | **Input – 3 file văn bản** | **Output** |
|---|---|
| **SINHVIEN.in**  2  B15DCKT150  NGUYEN NGOC SON  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  NguyeN TrONg Tung  D15CQKT02-B  sv4@stu.ptit.edu.vn  **DN.in**  4  VIETTEL  TAP DOAN VIEN THONG QUAN DOI VIETTEL  40  FSOFT  CONG TY TNHH PHAN MEM FPT - FPT SOFTWARE  300  VNPT  TAP DOAN BUU CHINH VIEN THONG VIET NAM  200  SUN  SUN\*  50  **THUCTAP.in**  2  B15DCKT150 VIETTEL  B15DCKT199 SUN  1  SUN | DANH SACH THUC TAP TAI SUN\*:  B15DCKT199 Nguyen Trong Tung D15CQKT02-B |

### TN02012 - TÍNH LƯƠNG

Công ty XYZ mỗi năm đều cập nhật hồ sơ và gán lại mã cho nhân viên (có đúng 5 ký tự) theo quy tắc sau:

- Ký tự đầu tiên là phân loại nhân viên, có 4 nhóm là A, B, C, D
- Hai chữ số tiếp theo mô tả số năm công tác
- Hai ký tự cuối là mã phòng ban.
 
Dựa trên loại nhân viên và số năm công tác, hệ số nhân để tính lương được cho trong bảng sau:

![Alt text](./img/TN02012_1.png)

Mỗi nhân viên theo hợp đồng sẽ có một giá trị lương cơ bản có thể rất khác nhau. Lương tháng được tính bằng tích của lương cơ bản với số ngày công và hệ số nhân.

Cho trước danh sách phòng ban, gồm mã phòng và tên phòng. Cho trước các thông tin nhân viên gồm mã, tên, lương cơ bản (tính theo ngày – đơn vị nghìn VNĐ) và số ngày công. Hãy tính toán và in ra bảng lương nhân viên trong tháng.

**Input**

Dòng đầu ghi số phòng ban, mỗi phòng ban viết trên một dòng gồm mã phòng và tên phòng.

Tiếp theo là một dòng ghi số nhân viên, mỗi nhân viên ghi trên 4 dòng gồm mã, tên, lương cơ bản (tính theo ngày), số ngày công.

**Output**

Lập bảng lương của nhân viên theo đúng thứ tự nhập. Mỗi nhân viên cần ghi ra các thông tin sau đây trên một dòng:

- Mã nhân viên
- Tên nhân viên
- Phòng ban
- Lương tháng
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  HC Hanh chinh  KH Ke hoach Dau tu  2  C06HC  Tran Binh Minh  65  25  D03KH  Le Hoa Binh  59  24 | C06HC Tran Binh Minh Hanh chinh 16250000  D03KH Le Hoa Binh Ke hoach Dau tu 11328000 |

## QUAN HỆ GIỮA CÁC LỚP

### J06001 - TÍNH TOÁN HÓA ĐƠN BÁN QUẦN ÁO

Cửa hàng quần áo bán một số loại sản phẩm, mỗi loại được chia thành hai loại: loại 1 và loại 2 với giá bán khác nhau.

Loại sản phẩm được mô tả gồm:

- Mã loại: 2 chữ cái
- Tên sản phẩm
- Đơn giá loại 1
- Đơn giá loại 2
 
Mỗi hóa đơn mua hàng sẽ có 2 thông tin:

- Mã hóa đơn, ban đầu chỉ có 3 ký tự 
    - Hai ký tự đầu tương ứng với mã loại
    - Tiếp theo là chữ số 1 hoặc 2 cho biết loại sản phẩm
 
Khi nhập dữ liệu, mã hóa đơn được bổ sung dấu gạch ngang và thứ tự hóa đơn, tính từ 001.

- Số lượng mua
 
Hãy lập bảng tính tiền phải trả cho mỗi hóa đơn, biết rằng hóa đơn có thể có giảm giá tính theo quy tắc sau:

- Nếu số lượng &gt;= 150 thì Giảm giá = 50% \* Thành tiền
- Nếu số lượng &gt;= 100 thì Giảm giá = 30% \* Thành tiền
- Nếu số lượng &gt;= 50 thì Giảm giá = 15% \* Thành tiền
 
**Input**

Dòng đầu ghi số loại sản phẩm. Thông tin về loại sản phẩm ghi trên 4 dòng gồm: mã, tên, giá loại 1, giá loại 2.

Tiếp theo là một dòng ghi số lượng hóa đơn. Mỗi hóa đơn chỉ có 1 dòng ghi mã hóa đơn ban đầu (3 ký tự) và số lượng mua.

**Output**

Ghi ra danh sách hóa đơn theo đúng thứ tự nhập gồm các thông tin:

- Mã hóa đơn (đầy đủ)
- Tên sản phẩm
- Số tiền giảm giá
- Số tiền phải trả
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  AT  Ao thun  80000  45000  QJ  Quan Jean  220000  125000  2  AT1 95  QJ2 105 | AT1-001 Ao thun 1140000 6460000  QJ2-002 Quan Jean 3937500 9187500 |

### J06002 - SẮP XẾP HÓA ĐƠN BÁN QUẦN ÁO

Cửa hàng quần áo bán một số loại sản phẩm, mỗi loại được chia thành hai loại: loại 1 và loại 2 với giá bán khác nhau.

Loại sản phẩm được mô tả gồm:

- Mã loại: 2 chữ cái
- Tên sản phẩm
- Đơn giá loại 1
- Đơn giá loại 2
 
Mỗi hóa đơn mua hàng sẽ có 2 thông tin:

- Mã hóa đơn, ban đầu chỉ có 3 ký tự 
    - Hai ký tự đầu tương ứng với mã loại
    - Tiếp theo là chữ số 1 hoặc 2 cho biết loại sản phẩm
 
Khi nhập dữ liệu, mã hóa đơn được bổ sung dấu gạch ngang và thứ tự hóa đơn, tính từ 001.

- Số lượng mua
 
Hãy lập bảng tính tiền phải trả cho mỗi hóa đơn, biết rằng hóa đơn có thể có giảm giá tính theo quy tắc sau:

- Nếu số lượng &gt;= 150 thì Giảm giá = 50% \* Thành tiền
- Nếu số lượng &gt;= 100 thì Giảm giá = 30% \* Thành tiền
- Nếu số lượng &gt;= 50 thì Giảm giá = 15% \* Thành tiền
 
**Input**

Dòng đầu ghi số loại sản phẩm. Thông tin về loại sản phẩm ghi trên 4 dòng gồm: mã, tên, giá loại 1, giá loại 2.

Tiếp theo là một dòng ghi số lượng hóa đơn. Mỗi hóa đơn chỉ có 1 dòng ghi mã hóa đơn ban đầu (3 ký tự) và số lượng mua.

**Output**

Ghi ra danh sách hóa đơn được sắp xếp theo số tiền phải trả giảm dần gồm các thông tin (biết rằng không có 2 hóa đơn nào có số tiền bằng nhau). Mỗi hóa đơn gồm các thông tin:

- Mã hóa đơn (đầy đủ)
- Tên sản phẩm
- Số tiền giảm giá
- Số tiền phải trả
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  AT  Ao thun  80000  45000  QJ  Quan Jean  220000  125000  2  AT1 95  QJ2 105 | QJ2-002 Quan Jean 3937500 9187500  AT1-001 Ao thun 1140000 6460000 |

### J06003 - QUẢN LÝ BÀI TẬP NHÓM – 1

Lớp học LTHĐT được chia thành các nhóm. Mỗi nhóm sẽ đăng ký một bài tập. Hãy tra cứu danh sách dữ liệu vào và liệt kê danh sách của các nhóm được yêu cầu và bài tập mà nhóm đó cần thực hiện.

**Input**

Dòng đầu ghi 2 số N và M (N không quá 100, M &lt; N) là số sinh viên và số nhóm.

Mỗi sinh viên ghi 4 dòng gồm:

- Mã sinh viên: không quá 15 ký tự
- Họ tên: Không quá 50 ký tự
- Số điện thoại: không quá 15 ký tự số
- Số thứ tự nhóm (đảm bảo từ 1 đến M).
 
Tiếp theo là M dòng, mỗi dòng ghi tên một bài tập lớn ứng với thứ tự nhóm từ 1 đến M. Độ dài tên bài tập không quá 200 ký tự.

Tiếp theo là một dòng ghi số Q là số truy vấn

Tiếp theo là Q dòng, mỗi dòng ghi số thứ tự nhóm cần truy vấn thông tin.

**Output**

Ghi ra danh sách nhóm theo từng truy vấn, giữ nguyên thứ tự thành viên ban đầu. Sau đó là bài tập được giao cho nhóm. Mẫu trình bày danh sách như trong ví dụ.

**Ví dụ**

 | **Input** |
|---|
| 5 2  B17DTCN001  Nguyen Chi Linh  0987345543  1  B17DTCN011  Vu Viet Thang  0981234567  1  B17DTCN023  Pham Trong Thang  0992123456  1  B17DTCN022  Nguyen Van Quyet  0977865432  2  B17DTCN031  Ngo Thanh Vien  0912313111  2  Xay dung website ban dien thoai truc tuyen  Xay dung ung dung quan ly benh nhan Covid-19  1  1 |
| **Output** |
| DANH SACH NHOM 1:  B17DTCN001 Nguyen Chi Linh 0987345543  B17DTCN011 Vu Viet Thang 0981234567  B17DTCN023 Pham Trong Thang 0992123456  Bai tap dang ky: Xay dung website ban dien thoai truc tuyen |

### J06004 - QUẢN LÝ BÀI TẬP NHÓM – 2

Lớp học LTHĐT được chia thành các nhóm. Mỗi nhóm sẽ đăng ký một bài tập. Hãy liệt kê toàn bộ danh sách sinh viên theo thứ tự sắp xếp mã sinh viên tăng dần và thứ tự nhóm, tên bài tập nhóm mà từng sinh viên cần thực hiện.

**Input**

Dòng đầu ghi 2 số N và M (N không quá 100, M &lt; N) là số sinh viên và số nhóm.

Mỗi sinh viên ghi 4 dòng gồm:

- Mã sinh viên: không quá 15 ký tự
- Họ tên: Không quá 50 ký tự
- Số điện thoại: không quá 15 ký tự số
- Số thứ tự nhóm (đảm bảo từ 1 đến M).
 
Tiếp theo là M dòng, mỗi dòng ghi tên một bài tập lớn ứng với thứ tự nhóm từ 1 đến M. Độ dài tên bài tập không quá 200 ký tự.

**Output**

Ghi ra danh sách tất cả sinh viên theo thứ tự mã sinh viên tăng dần (thứ tự từ điển). Mỗi sinh viên bao gồm: mã, họ tên, số điện thoại, số thứ tự nhóm, tên bài tập nhóm.

**Ví dụ**

 | **Input** |
|---|
| 5 2  B17DTCN001  Nguyen Chi Linh  0987345543  1  B17DTCN011  Vu Viet Thang  0981234567  1  B17DTCN023  Pham Trong Thang  0992123456  1  B17DTCN022  Nguyen Van Quyet  0977865432  2  B17DTCN031  Ngo Thanh Vien  0912313111  2  Xay dung website ban dien thoai truc tuyen  Xay dung ung dung quan ly benh nhan Covid-19 |
| **Output** |
| B17DTCN001 Nguyen Chi Linh 0987345543 1 Xay dung website ban dien thoai truc tuyen  B17DTCN011 Vu Viet Thang 0981234567 1 Xay dung website ban dien thoai truc tuyen  B17DTCN022 Nguyen Van Quyet 0977865432 2 Xay dung ung dung quan ly benh nhan Covid-19  B17DTCN023 Pham Trong Thang 0992123456 1 Xay dung website ban dien thoai truc tuyen  B17DTCN031 Ngo Thanh Vien 0912313111 2 Xay dung ung dung quan ly benh nhan Covid-19 |

### J06005 - QUẢN LÝ BÁN HÀNG – 1

Khai báo lớp Khách hàng với các thuộc tính:

- Mã khách hàng: tự động tăng, tính từ KH001
- Tên khách hàng: xâu ký tự độ dài không quá 50
- Giới tính: Nam hoặc Nu
- Ngày sinh: Theo đúng chuẩn dd/mm/yyyy
- Địa chỉ: xâu ký tự độ dài không quá 100
 
Khai báo lớp Mặt hàng với các thuộc tính:

- Mã mặt hàng: tự động tăng, tính từ MH001
- Tên mặt hàng: xâu ký tự độ dài không quá 100
- Đơn vị tính: xâu ký tự độ dài không quá 10
- Giá mua: số nguyên dương không quá 7 chữ số
- Giá bán: số nguyên dương không quá 7 chữ số
 
Khai báo lớp Hóa đơn trong đó có các thông tin:

- Mã hóa đơn
- Khách hàng
- Mặt hàng
- Số lượng (không quá 1000)
 
Viết chương trình nhập danh sách hóa đơn và in danh sách ra màn hình.

**Input**

Dòng đầu ghi số N là số khách hàng (không quá 20).

Tiếp theo là thông tin của N khách hàng, mỗi khách hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

Dòng tiếp theo ghi số M là số mặt hàng (không quá 40).

Tiếp theo là thông tin của M mặt hàng, mỗi mặt hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

Dòng tiếp theo ghi số K là số hóa đơn (không quá 100)

Mỗi hóa đơn ghi trên **1 dòng** gồm 3 thông tin theo đúng thứ tự đã mô tả (không có mã).

**Output**

Ghi ra danh sách hóa đơn theo đúng thứ tự nhập, trong đó gồm các thông tin sau, mỗi thông tin cách nhau đúng một khoảng trống.

- Mã hóa đơn
- Tên khách hàng
- Địa chỉ
- Tên mặt hàng
- Đơn vị tính
- Giá mua
- Giá bán
- Số lượng
- Thành tiền
 
**Ví dụ**

 | **Input** |
|---|
| 2  Nguyen Van Nam  Nam  12/12/1997  Mo Lao-Ha Dong-Ha Noi  Tran Van Binh  Nam  11/14/1995  Phung Khoang-Nam Tu Liem-Ha Noi  2  Ao phong tre em  Cai  25000  41000  Ao khoac nam  Cai  240000  515000  3  KH001 MH001 2  KH001 MH002 3  KH002 MH002 4 |
| **Output** |
| HD001 Nguyen Van Nam Mo Lao-Ha Dong-Ha Noi Ao phong tre em Cai 25000 41000 2 82000  HD002 Nguyen Van Nam Mo Lao-Ha Dong-Ha Noi Ao khoac nam Cai 240000 515000 3 1545000  HD003 Tran Van Binh Phung Khoang-Nam Tu Liem-Ha Noi Ao khoac nam Cai 240000 515000 4 2060000 |

### J06006 - QUẢN LÝ BÁN HÀNG – 2

Khai báo lớp Khách hàng với các thuộc tính:

- Mã khách hàng: tự động tăng, tính từ KH001
- Tên khách hàng: xâu ký tự độ dài không quá 50
- Giới tính: Nam hoặc Nu
- Ngày sinh: Theo đúng chuẩn dd/mm/yyyy
- Địa chỉ: xâu ký tự độ dài không quá 100
 
Khai báo lớp Mặt hàng với các thuộc tính:

- Mã mặt hàng: tự động tăng, tính từ MH001
- Tên mặt hàng: xâu ký tự độ dài không quá 100
- Đơn vị tính: xâu ký tự độ dài không quá 10
- Giá mua: số nguyên dương không quá 7 chữ số
- Giá bán: số nguyên dương không quá 7 chữ số
 
Khai báo lớp Hóa đơn là bạn của lớp Khách hàng và lớp Mặt hàng trong đó có các thông tin:

- Mã hóa đơn
- Mã khách hàng
- Mã mặt hàng
- Số lượng (không quá 1000)
- Lợi nhuận
 
Viết chương trình nhập danh sách hóa đơn, sắp xếp theo lợi nhuận giảm dần và in danh sách ra màn hình.

**Input**

Dòng đầu ghi số N là số khách hàng (không quá 20).

Tiếp theo là thông tin của N khách hàng, mỗi khách hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

Dòng tiếp theo ghi số M là số mặt hàng (không quá 40).

Tiếp theo là thông tin của M mặt hàng, mỗi mặt hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

Dòng tiếp theo ghi số K là số hóa đơn (không quá 100)

Mỗi hóa đơn ghi trên **1 dòng** gồm 3 thông tin theo đúng thứ tự đã mô tả (không có mã và lợi nhuận).

**Output**

Ghi ra danh sách hóa đơn đã sắp xếp, trong đó gồm các thông tin sau, mỗi thông tin cách nhau đúng một khoảng trống.

- Mã hóa đơn
- Tên khách hàng
- Địa chỉ
- Tên mặt hàng
- Số lượng
- Thành tiền
- Lợi nhuận
 
**Ví dụ**

 | **Input** |
|---|
| 2  Nguyen Van Nam  Nam  12/12/1997  Mo Lao-Ha Dong-Ha Noi  Tran Van Binh  Nam  11/14/1995  Phung Khoang-Nam Tu Liem-Ha Noi  2  Ao phong tre em  Cai  25000  41000  Ao khoac nam  Cai  240000  515000  3  KH001 MH001 2  KH001 MH002 3  KH002 MH002 4 |
| **Output** |
| HD003 Tran Van Binh Phung Khoang-Nam Tu Liem-Ha Noi Ao khoac nam 4 2060000 1100000  HD002 Nguyen Van Nam Mo Lao-Ha Dong-Ha Noi Ao khoac nam 3 1545000 825000  HD001 Nguyen Van Nam Mo Lao-Ha Dong-Ha Noi Ao phong tre em 2 82000 32000 |

### J06007 - BẢNG TÍNH GIỜ CHUẨN

Tại trường đại học ABC, môn học có mã môn và tên môn, thông tin của mỗi giảng viên gồm mã giảng viên, tên giảng viên.

Một giảng viên khi tham gia giảng dạy một môn học sẽ được ghi nhận số giờ chuẩn. Giả sử với mỗi môn học thì một giảng viên chỉ giảng dạy nhiều nhất 1 lớp học phần.

Viết chương trình lập bảng tính toán giờ chuẩn cho từng giảng viên.

**Input**

Dòng đầu ghi số môn học. Mỗi môn học viết trên một dòng gồm mã môn, sau đó đến khoảng trống rồi đến tên môn.

Tiếp theo là một dòng ghi số giảng viên. Mỗi giảng viên viết trên một dòng gồm mã giảng viên và tên giảng viên.

Tiếp theo là một dòng ghi số lớp học phần. Mỗi lớp học phần sẽ ghi trên một dòng gồm mã giảng viên, mã môn sau đó đến giờ chuẩn (dạng số thực).

**Output**

Ghi ra danh sách giảng viên theo thứ tự nhập và tổng giờ chuẩn tính được. Thông tin cần liệt kê chỉ bao gồm tên giảng viên và tổng số giờ chuẩn (viết chính xác đến 2 số phần thập phân).

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  INT1155 Tin hoc co so 2  INT1306 Cau truc du lieu va giai thuat  2  GV01 Nguyen Van An  GV02 Hoang Binh Minh  2  GV01 INT1155 113.2  GV02 INT1306 126.72 | Nguyen Van An 113.20  Hoang Binh Minh 126.72 |

### J06008 - TÍNH GIỜ CHUẨN CHO TỪNG GIẢNG VIÊN

Tại trường đại học ABC, môn học có mã môn và tên môn, thông tin của mỗi giảng viên gồm mã giảng viên, tên giảng viên.

Một giảng viên khi tham gia giảng dạy một môn học sẽ được ghi nhận số giờ chuẩn. Giả sử với mỗi môn học thì một giảng viên chỉ giảng dạy nhiều nhất 1 lớp học phần.

Viết chương trình lập bảng tính toán giờ chuẩn cho từng giảng viên.

**Input**

Dòng đầu ghi số môn học. Mỗi môn học viết trên một dòng gồm mã môn, sau đó đến khoảng trống rồi đến tên môn.

Tiếp theo là một dòng ghi số giảng viên. Mỗi giảng viên viết trên một dòng gồm mã giảng viên và tên giảng viên.

Tiếp theo là một dòng ghi số lớp học phần. Mỗi lớp học phần sẽ ghi trên một dòng gồm mã giảng viên, mã môn sau đó đến giờ chuẩn (dạng số thực).

Tiếp theo là một dòng ghi mã giảng viên cần thống kê giờ chuẩn.

**Output**

Ghi ra tên giảng viên sau đó lần lượt các lớp môn giảng dạy (theo đúng thứ tự nhập), giờ chuẩn từng lớp và tổng giờ chuẩn theo mẫu trong ví dụ. Chú ý: tổng giờ chuẩn ghi 2 số phần thập phân.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  INT1155 Tin hoc co so 2  INT1306 Cau truc du lieu va giai thuat  2  GV01 Nguyen Van An  GV02 Hoang Binh Minh  2  GV01 INT1155 113.2  GV02 INT1306 126.72  GV01 | Giang vien: Nguyen Van An  Tin hoc co so 2 113.2  Tong: 113.20 |

## VÀO RA FILE

### J07001 - ĐỌC FILE VĂN BẢN

Cho file văn bản **DATA.in**

Hãy đọc toàn bộ nội dung của file và in ra màn hình theo đúng định dạng ban đầu.

**Ví dụ:**

 | **DATA.in** | **Output** |
|---|---|
| Lap trinh huong doi tuong  voi Java | Lap trinh huong doi tuong  voi Java |

### J07002 - TÍNH TỔNG

Cho file dữ liệu dạng văn bản DATA.in có thể chứa cả số và ký tự.

Hãy lọc ra các số nguyên int trong file và tính tổng các số đó.

Chú ý: file dữ liệu có rất nhiều dòng với rất nhiều số và ký tự xen kẽ nhau. Chỉ tính tổng các số thỏa mãn điều kiện là số kiểu int.

**Input**

File văn bản DATA.in có không quá 1000 dòng.

**Output**

Ghi ra giá trị tổng các số tính được.

**Ví dụ**

 | **DATA.in** | **Output** |
|---|---|
| 12 3 4 5 6 7  Aaa 1 1 Bbb XXX yyy 5 5  999999999999999999999999  9 | 58 |

### J07004 - SỐ KHÁC NHAU TRONG FILE  - 1

Cho file văn bản DATA.in có không quá 100000 số nguyên dương, giá trị các số nhỏ hơn 1000.

Hãy liệt kê các số khác nhau xuất hiện trong file và số lần xuất hiện của từng số đó.

**Input**

File DATA.in có không quá 100000 số nguyên dương.

**Output**

Ghi ra các số khác nhau và số lần xuất hiện theo thứ tự tăng dần

**Ví dụ**

 | **DATA.in** | **Output** |
|---|---|
| 17 20 25 20 15 10 24 17 25 17 22 11 23 18  14 25 12 10 12 17 21 25 | 10 2  11 1  12 2  14 1  15 1  17 4  18 1  20 2  21 1  22 1  23 1  24 1  25 4 |

### J07005 - SỐ KHÁC NHAU TRONG FILE  - 2

Cho file **nhị phân** DATA.IN có đúng 100000 số nguyên dương, giá trị các số nhỏ hơn 1000.

Hãy liệt kê các số khác nhau xuất hiện trong file và số lần xuất hiện của từng số đó.

**Input**

File DATA.IN có 100000 số nguyên dương.

**Output**

Ghi ra các số khác nhau và số lần xuất hiện theo thứ tự tăng dần

**Ví dụ:**

 | **DATA.IN** | **Output** |
|---|---|
| File nhị phân theo mô tả đề bài | Liệt kê các số tăng dần, ví dụ:  10 2  21 1  25 4 |

### J07007 - LIỆT KÊ TỪ KHÁC NHAU

Cho file văn bản VANBAN.in.

Một từ được định nghĩa là một dãy ký tự liên tiếp không có khoảng trống, dấu tab hay dấu xuống dòng. Tạm thời chưa xét đến các dấu câu trong bải toán này.

Hãy chuyển tất cả các từ về dạng chữ thường sau đó liệt kê các từ khác nhau xuất hiện trong file VANBAN.in theo thứ tự từ điển.

**Input**

File VANBAN.in có không quá 200 dòng.

**Output**

Ghi ra danh sách các từ khác nhau xuất hiện trong file. Mỗi từ trên một dòng theo thứ tự từ điển.

**Ví dụ**

 | **VANBAN.in** | **Output** |
|---|---|
| lap trinh Huong doi tuong  lap trinh Huong thanh phan | doi  huong  lap  phan  thanh  trinh  tuong |

### J07010 - DANH SÁCH SINH VIÊN TRONG FILE - 2

Khai báo lớp Sinh Viên gồm các thông tin: Mã SV, Họ tên, Ngày sinh, Lớp và Điểm GPA (dạng số thực).

Đọc thông tin N sinh viên từ file văn bản **SV.in** (không có mã sinh viên) và in ra lần lượt màn hình mỗi dòng 1 sinh viên theo đúng thứ tự ban đầu. Trong đó Mã SV được tự tạo ra theo quy tắc thêm mã **B20DCCN** sau đó là giá trị nguyên tự động tăng tính từ 001 (tối đa là 099). Ngày sinh được chuẩn hóa về dạng dd/mm/yyyy

**Input (file SV.in)**

Dòng đầu tiên ghi số sinh viên N (0 &lt; N &lt; 50).

Mỗi sinh viên ghi trên 4 dòng lần lượt là Họ tên, Lớp, Ngày sinh và Điểm GPA.

Trong đó:

- Họ tên không quá 30 chữ cái.
- Lớp theo đúng định dạng thường dùng ở PTIT
- Ngày sinh có đủ 3 phần ngày tháng năm nhưng có thể chưa đúng chuẩn dd/mm/yyyy.
- Điểm GPA đảm bảo trong thang điểm 4 với 2 nhiều nhất 2 số sau dấu phẩy.
 
**Output**

Ghi ra màn hình danh sách lần lượt các sinh viên có đầy đủ Mã sinh viên, Họ tên, Lớp, Ngày sinh (đã chuẩn hóa về dạng dd/mm/yyyy), Điểm GPA (với đúng 2 số sau dấu phẩy).

Mỗi sinh viên ghi trên 1 dòng, mỗi thông tin cách nhau 1 khoảng trống.

**Ví dụ**

 | **SV.in** | **Output** |
|---|---|
| 1  Nguyen Van An  D20CQCN01-B  2/12/2002  3.19 | B20DCCN001 Nguyen Van An D20CQCN01-B 02/12/2002 3.19 |

### J07011 - THỐNG KÊ TỪ KHÁC NHAU TRONG FILE VĂN BẢN

Cho file văn bản VANBAN.in có N dòng trong đó có thể có các dấu câu như dẩy phẩy (,) dấu chấm (.) dấu chấm hỏi (?) dấu chấm cảm (!) dấu hai chấm (:) dấu chấm phẩy (;) dấu ngoặc đơn, dấu gạch ngang (-), dấu gạch chéo (/).

Hãy liệt kê các từ khác nhau xuất hiện trong đoạn văn bản theo thứ tự số lần xuất hiện giảm dần.

Chú ý:

- Khi thống kê thì không phân biệt chữ hoa, chữ thường.
- Bỏ qua các dấu câu đã liệt kê ở trên khi tách từ
 
**Input - file văn bản VANBAN.in**

Dòng đầu ghi số N không quá 1000.

Tiếp theo là N dòng mô tả văn bản. Mỗi dòng không quá 500 ký tự.

**Output**

Ghi ra danh sách các từ (ở dạng in thường) theo thứ tự số lần xuất hiện giảm dần.

Trong trường hợp số lần xuất hiện bằng nhau thì liệt kê theo thứ tự từ điển tăng dần.

**Ví dụ**

 | **Input** |
|---|
| 3  PTIT duy tri hoc phi on dinh nam 2019 va khong tang trong nam 2020-2021 va 2021-2022!  Khi dich benh xuat hien PTIT trich hon 6 ty dong ho tro sinh vien PTIT  voi muc ho tro 500000 dong/sinh vien PTIT. |
| **Output** |
| ptit 4  2021 2  dong 2  ho 2  nam 2  sinh 2  tro 2  va 2  vien 2  2019 1  2020 1  2022 1  500000 1  6 1  benh 1  dich 1  dinh 1  duy 1  hien 1  hoc 1  hon 1  khi 1  khong 1  muc 1  on 1  phi 1  tang 1  tri 1  trich 1  trong 1  ty 1  voi 1  xuat 1 |

### J07012 - THỐNG KÊ TỪ KHÁC NHAU TRONG FILE NHỊ PHÂN

Cho file nhị phân DATA.in có một ArrayList&lt;String&gt; được ghi vào file theo kiểu writeObject().

Người ta định nghĩa một từ là dãy ký tự không chứa khoảng trắng, dấu tab và dấu xuống dòng, đồng thời không tính các dấu câu như dẩy phẩy (,) dấu chấm (.) dấu chấm hỏi (?) dấu chấm cảm (!) dấu hai chấm (:) dấu chấm phẩy (;) dấu ngoặc đơn, dấu gạch ngang (-), dấu gạch chéo (/).

Hãy đọc dữ liệu từ file và liệt kê các từ khác nhau xuất hiện theo thứ tự số lần xuất hiện giảm dần.

Chú ý:

- Khi thống kê thì không phân biệt chữ hoa, chữ thường.
- Bỏ qua các dấu câu đã liệt kê ở trên khi tách từ
 
**Input - file nhị phân DATA.in**

Chứa duy nhất một ArrayList&lt;String&gt;

**Output**

Ghi ra danh sách các từ (ở dạng in thường) theo thứ tự số lần xuất hiện giảm dần.

Trong trường hợp số lần xuất hiện bằng nhau thì liệt kê theo thứ tự từ điển tăng dần.

 **Ví dụ**

 | **Input** |
|---|
| File nhị phân DATA.in theo mô tả trong đề bài. |
| **Output** |
| Ghi ra theo yêu cầu đề bài, mỗi từ trên một dòng đi kèm số lần xuất hiện. Ví dụ:  tuong 99  huong 11  lap 10  trinh 8  doi 5 |

### J07013 - DANH SÁCH SINH VIÊN TRONG FILE NHỊ PHÂN

Khai báo lớp SinhVien gồm các thông tin: ***ma, ten, lop*** kiểu String; ***ngaysinh*** (kiểu Date), và ***gpa*** (dạng số thực float). Viết hàm khởi tạo sinh viên trong đó Mã SV được tự tạo ra theo quy tắc thêm mã **B20DCCN** từ giá trị số nguyên id (là thứ tự truyền vào hàm khởi tạo). Ngày sinh nhận tham số khởi tạo là xâu ký tự và được chuẩn hóa về dạng dd/mm/yyyy.

Nhập một ArrayList&lt;SinhVien&gt; từ file nhị phân **SV.in** và in ra lần lượt màn hình mỗi dòng 1 sinh viên theo đúng thứ tự ban đầu.

Chú ý: khai báo package trong bài này là danhsachsinhvien1

**Input (file SV.in)**

Có một ArrayList&lt;SinhVien&gt; được ghi ra với hàm writeObject();

**Output**

Ghi ra màn hình danh sách lần lượt các sinh viên có đầy đủ Mã sinh viên, Họ tên, Lớp, Ngày sinh (đã chuẩn hóa về dạng dd/mm/yyyy), Điểm GPA (với đúng 2 số sau dấu phẩy).

Mỗi sinh viên ghi trên 1 dòng, mỗi thông tin cách nhau 1 khoảng trống.

**Ví dụ:**

 | **SV.in** | **Output** |
|---|---|
| File nhị phân theo mô tả trong đề bài. | Danh sách sinh viên đọc được theo đúng thứ tự ban đầu, mồi sinh viên in ra ở dạng sau:  B20DCCN001 Nguyen Van An D20CQCN01-B 02/12/2002 3.19 |

### J07014 - HỢP VÀ GIAO CỦA HAI FILE VĂN BẢN

Cho hai file DATA1.in và DATA2.in.

Một từ được định nghĩa là một dãy ký tự liên tiếp không có khoảng trống, dấu tab hay dấu xuống dòng. Tạm thời chưa xét đến các dấu câu trong bải toán này.

Hãy viết chương trình liệt kê hợp và giao của hai tập từ khác nhau trong hai file.

Các từ được liệt kê theo thứ tự từ điển.

**Input**

Hai file văn bản DATA1.in và DATA2.in, có không quá 200 dòng.

**Output**

Hợp và giao của hai tập từ khác nhau trong hai file ban đầu. Mỗi tập trên một dòng, các từ liệt kê theo thứ tự từ điển và cách nhau đúng một khoảng trống.

**Ví dụ**

 | **DATA1.in** | **Output** |
|---|---|
| lap trinh huong doi tuong  ngon ngu lap trinh C++ | ban c++ co doi huong lap ngon ngu phan thanh trinh tuong  huong lap trinh |
| **DATA2.in** |
| lap trinh co ban  lap trinh huong thanh phan |

### J07015 - SỐ NGUYÊN TỐ TRONG FILE NHỊ PHÂN

Cho file nhị phân SONGUYEN.in trong đó ghi một ArrayList&lt;Integer&gt; theo kiểu object. Các giá trị đều nguyên dương và nhỏ hơn 10000.

Hãy viết chương trình trình liệt kê các số nguyên tố khác nhau xuất hiện trong file theo thứ tự tăng dần và số lần xuất hiện của các số đó.

**Input**

File nhị phân SONGUYEN.in

**Output**

Ghi ra các số nguyên tố khác nhau theo thứ tự tăng dần và số lần xuất hiện.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| File SONGUYEN.in theo mô tả đề bài | Danh sách các số nguyên tố tăng dần và số lần xuất hiện. Ví dụ:  2 17  11 15  997 8 |

### J07016 - SỐ NGUYÊN TỐ TRONG HAI FILE NHỊ PHÂN

Cho hai file nhị phân DATA1.in và DATA2.in trong đó mỗi file đều có một ArrayList&lt;Integer&gt; được ghi theo kiểu object. Các giá trị số đều nguyên dương và nhỏ hơn 10000.

Hãy liệt kê các số nguyên tố xuất hiện trong cả hai file trên.

**Input**

Hai file nhị phân như mô tả.

**Output**

Ghi ra màn hình danh sách các số nguyên tố xuất hiện trong cả hai file. Mỗi số thỏa mãn liệt kê trên một dòng theo thứ tự tăng dần, gồm giá trị số nguyên tố, số lần xuất hiện trong DATA1.in và số lần xuất hiện trong DATA2.in.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| File nhị phân DATA1.in và DATA2.in theo mô tả đề bài | Danh sách các số nguyên tố tăng dần và số lần xuất hiện trong 2 file. Ví dụ:  2 4 19  7 15 4  997 8 1 |

### J07017 - LỚP PAIR (GENERIC)

Khai báo lớp Pair kiểu Generic để ghép cặp hai đối tượng bất kỳ.

Sử dụng lớp Pair ghép cặp hai số nguyên để giải quyết bài toán sau (chú ý viết hàm main đúng theo mẫu).

Nhập số tự nhiên N, hãy tìm cặp số nguyên tố đầu tiên có tổng là N.

Nếu không tồn tại cặp số nguyên tố có tổng bằng N, hãy đưa ra -1.

**Input**: **File văn bản DATA.in**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm là một số N được ghi trên một dòng.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤ N ≤106
 
**Output**:

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output:** |
|---|---|
| 2  4  8 | 2 2  3 5 |

### J07018 - CHUẨN HÓA DANH SÁCH SINH VIÊN

lớp Sinh Viên gồm các thông tin: Mã SV, Họ tên, Ngày sinh, Lớp và Điểm GPA (dạng số thực).

Đọc thông tin N thí sinh từ file văn bản SINHVIEN.in (không có mã sinh viên) và in ra lần lượt màn hình mỗi dòng 1 sinh viên theo đúng thứ tự ban đầu. Trong đó Mã SV được tự tạo ra theo quy tắc thêm mã **B20DCCN** sau đó là giá trị nguyên tự động tăng tính từ 001 (tối đa là 099).

Họ tên được xử lý đưa về dạng chuẩn.

Ngày sinh được chuẩn hóa về dạng dd/mm/yyyy

**Input: file SINHVIEN.in**

Dòng đầu tiên ghi số sinh viên N (0 &lt; N &lt; 50).

Mỗi sinh viên ghi trên 4 dòng lần lượt là Họ tên, Lớp, Ngày sinh và Điểm GPA.

Trong đó:

- Họ tên không quá 30 chữ cái.
- Lớp theo đúng định dạng thường dùng ở PTIT
- Ngày sinh có đủ 3 phần ngày tháng năm nhưng có thể chưa đúng chuẩn dd/mm/yyyy.
- Điểm GPA đảm bảo trong thang điểm 4 với 2 nhiều nhất 2 số sau dấu phẩy.
 
**Output**

Ghi ra danh sách lần lượt các sinh viên có đầy đủ Mã sinh viên, Họ tên, Lớp, Ngày sinh (đã chuẩn hóa), điểm GPA (với đúng 2 số sau dấu phẩy).

Mỗi sinh viên ghi trên 1 dòng, mỗi thông tin cách nhau 1 khoảng trống.

**Ví dụ**

 | **Input - SINHVIEN.in** | **Output** |
|---|---|
| 1  nGuyEn vaN biNH  D20CQCN01-B  2/12/2002  3.1 | B20DCCN001 Nguyen Van Binh D20CQCN01-B 02/12/2002 3.10 |

### J07019 - HÓA ĐƠN - 1

Cửa hàng quần áo bán một số loại sản phẩm, mỗi loại được chia thành hai loại: loại 1 và loại 2 với giá bán khác nhau.

Loại sản phẩm được mô tả gồm:

- Mã loại: 2 chữ cái
- Tên sản phẩm
- Đơn giá loại 1
- Đơn giá loại 2
 
Mỗi hóa đơn mua hàng sẽ có 2 thông tin:

- Mã hóa đơn, ban đầu chỉ có 3 ký tự
    - Hai ký tự đầu tương ứng với mã loại
    - Tiếp theo là chữ số 1 hoặc 2 cho biết loại sản phẩm
 
Khi nhập dữ liệu, mã hóa đơn được bổ sung dấu gạch ngang và thứ tự hóa đơn, tính từ 001.

- Số lượng mua
 
Hãy lập bảng tính tiền phải trả cho mỗi hóa đơn, biết rằng hóa đơn có thể có giảm giá tính theo quy tắc sau:

\- Nếu số lượng &gt;= 150 thì Giảm giá = 50% \* Thành tiền

\- Nếu số lượng &gt;= 100 thì Giảm giá = 30% \* Thành tiền

\- Nếu số lượng &gt;= 50 thì Giảm giá = 15% \* Thành tiền

**Input:** Có 2 file dữ liệu đều ở dạng file văn bản.

**File DATA1.in**

Dòng đầu ghi số loại sản phẩm. Thông tin về loại sản phẩm ghi trên 4 dòng gồm: mã, tên, giá loại 1, giá loại 2.

**File DATA2.in**

Dòng đầu ghi số lượng hóa đơn. Mỗi hóa đơn chỉ có 1 dòng ghi mã hóa đơn ban đầu (3 ký tự) và số lượng mua.

**Output**

Ghi ra danh sách hóa đơn theo đúng thứ tự nhập gồm các thông tin:

- Mã hóa đơn (đầy đủ)
- Tên sản phẩm
- Số tiền giảm giá
- Số tiền phải trả
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| **DATA1.in**  2  AT  Ao thun  80000  45000  QJ  Quan Jean  220000  125000  **DATA2.in**  2  AT1 95  QJ2 105 | AT1-001 Ao thun 1140000 6460000  QJ2-002 Quan Jean 3937500 9187500 |

### J07020 - HÓA ĐƠN - 2

Khai báo lớp Khách hàng với các thuộc tính:

- Mã khách hàng: tự động tăng, tính từ KH001
- Tên khách hàng: xâu ký tự độ dài không quá 50
- Giới tính: Nam hoặc Nu
- Ngày sinh: Theo đúng chuẩn dd/mm/yyyy
- Địa chỉ: xâu ký tự độ dài không quá 100
 
Khai báo lớp Mặt hàng với các thuộc tính:

- Mã mặt hàng: tự động tăng, tính từ MH001
- Tên mặt hàng: xâu ký tự độ dài không quá 100
- Đơn vị tính: xâu ký tự độ dài không quá 10
- Giá mua: số nguyên dương không quá 7 chữ số
- Giá bán: số nguyên dương không quá 7 chữ số
 
Khai báo lớp Hóa đơn trong đó có các thông tin:

- Mã hóa đơn
- Khách hàng
- Mặt hàng
- Số lượng (không quá 1000)
 
Viết chương trình nhập danh sách hóa đơn và in danh sách ra màn hình.

**Input - có 3 file văn bản**

**File KH.in**

Dòng đầu ghi số N là số khách hàng (không quá 20).

Tiếp theo là thông tin của N khách hàng, mỗi khách hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

**File MH.in**

Dòng đầu ghi số M là số mặt hàng (không quá 40).

Tiếp theo là thông tin của M mặt hàng, mỗi mặt hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

**File HD.in**

Dòng đầu theo ghi số K là số hóa đơn (không quá 100)

Mỗi hóa đơn ghi trên **1 dòng** gồm 3 thông tin theo đúng thứ tự đã mô tả (không có mã).

**Output**

Ghi ra danh sách hóa đơn theo đúng thứ tự nhập, trong đó gồm các thông tin sau, mỗi thông tin cách nhau đúng một khoảng trống.

- Mã hóa đơn
- Tên khách hàng
- Địa chỉ
- Tên mặt hàng
- Đơn vị tính
- Giá mua
- Giá bán
- Số lượng
- Thành tiền
 
**Ví dụ**

 | **Input** |
|---|
| **File KH.in**  2  Nguyen Van Nam  Nam  12/12/1997  Mo Lao-Ha Dong-Ha Noi  Tran Van Binh  Nam  11/14/1995  Phung Khoang-Nam Tu Liem-Ha Noi  **File MH.in**  2  Ao phong tre em  Cai  25000  41000  Ao khoac nam  Cai  240000  515000  **File HD.in**  3  KH001 MH001 2  KH001 MH002 3  KH002 MH002 4 |
| **Output** |
| HD001 Nguyen Van Nam Mo Lao-Ha Dong-Ha Noi Ao phong tre em Cai 25000 41000 2 82000  HD002 Nguyen Van Nam Mo Lao-Ha Dong-Ha Noi Ao khoac nam Cai 240000 515000 3 1545000  HD003 Tran Van Binh Phung Khoang-Nam Tu Liem-Ha Noi Ao khoac nam Cai 240000 515000 4 2060000 |

### J07021 - CHUẨN HÓA XÂU HỌ TÊN TRONG FILE

Một xâu họ tên được coi là viết chuẩn nếu chữ cái đầu tiên mỗi từ được viết hoa, các chữ  
 cái khác viết thường. Các từ cách nhau đúng một dấu cách và không có khoảng trống  
 thừa ở đầu và cuối xâu. Hãy viết chương trình đưa các xâu họ tên về dạng chuẩn.  
 **Input - file DATA.in:**

Có nhiều bộ test. Mỗi bộ test ghi trên một dòng xâu ký tự họ tên, không quá 80 ký tự.

Input kết thúc khi gặp xâu END  
 **Output:**

Với mỗi bộ test ghi ra xâu ký tự họ tên đã chuẩn hóa.  
 **Ví dụ:**

 | **DATA.in** | **Output** |
|---|---|
| nGuYEN vAN naM    tRan TRUNG hiEU    vO le hOA bINh  END | Nguyen Van Nam    Tran Trung Hieu    Vo Le Hoa Binh |

### J07022 - LOẠI BỎ SỐ NGUYÊN

Cho file dữ liệu dạng văn bản DATA.in có thể chứa cả số và ký tự.

Hãy loại bỏ các số nguyên int, sắp xếp các nội dung còn lại trong file theo thứ tự từ điển và in ra trên một dòng.

Chú ý: file dữ liệu có rất nhiều dòng với rất nhiều số và ký tự xen kẽ nhau.

**Input**

File văn bản DATA.in có không quá 1000 dòng. Dữ liệu đảm bảo số lượng các từ trong dãy kết quả nhỏ hơn 10000.

**Output**

Ghi ra các nội dung không thỏa mãn kiểu int trên một dòng, sắp xếp theo thứ tự từ điển, mỗi từ cách nhau một khoảng trống.

**Ví dụ**

 | **DATA.in** | **Output** |
|---|---|
| 12 3 4 5 6 7  Aaa 1 1 Bbb XXX yyy 5 5  999999999999999999999999  9 | 999999999999999999999999 Aaa Bbb XXX yyy |

### J07023 - NGUYÊN TỐ VÀ THUẬN NGHỊCH

Cho hai file nhị phân DATA1.in và DATA2.in trong đó mỗi file đều có một ArrayList&lt;Integer&gt; được ghi theo kiểu object. Các giá trị số đều nguyên dương và nhỏ hơn 10000.

Hãy liệt kê các số vừa nguyên tố vừa thuận nghịch xuất hiện trong cả hai file trên. Các số cần được liệt kê theo thứ tự tăng dần.

**Input**

Hai file nhị phân như mô tả.

**Output**

Ghi ra màn hình danh sách các số vừa nguyên tố vừa thuận nghịch xuất hiện trong cả hai file. Mỗi số thỏa mãn liệt kê trên một dòng theo thứ tự tăng dần, gồm giá trị số nguyên tố, số lần xuất hiện trong DATA1.in và số lần xuất hiện trong DATA2.in.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| File nhị phân DATA1.in và DATA2.in theo mô tả đề bài | Danh sách các số nguyên tố tăng dần và số lần xuất hiện trong 2 file. Ví dụ:  11 17 4  101 6 8  131 9 9 |

### J07024 - HIỆU CỦA HAI TẬP TỪ

Cho hai file văn bản DATA1.in và DATA2.in.

Một từ được định nghĩa là một dãy ký tự liên tiếp không có khoảng trống, dấu tab hay dấu xuống dòng. Tạm thời chưa xét đến các dấu câu trong bải toán này.

Hãy viết chương trình liệt kê tập hợp các từ có mặt trong file DATA1.in nhưng không có trong file DATA2.in và ngược lại.

Các từ được liệt kê theo thứ tự từ điển.

**Input**

Hai file văn bản DATA1.in và DATA2.in, có không quá 200 dòng.

**Output**

Dòng 1 ghi các từ có mặt trong file DATA1.in nhưng không có trong file DATA2.in.

Dòng 2 ghi các từ có mặt trong file DATA2.in nhưng không có trong file DATA1.in.

**Ví dụ**

 | **DATA1.in** | **Output** |
|---|---|
| lap trinh huong doi tuong  ngon ngu lap trinh C++ | c++ doi ngon ngu tuong    ban co phan thanh |
| **DATA2.in** |
| lap trinh co ban  lap trinh huong thanh phan |

### J07025 - DANH SÁCH KHÁCH HÀNG TRONG FILE

Bài toán quản lý danh sách khách hàng, trong đó mỗi Khách hàng có các thông tin:

- Mã khách hàng: tự động tăng, tính từ KH001
- Tên khách hàng: xâu ký tự độ dài không quá 50, cần đưa về dạng chuẩn
- Giới tính: Nam hoặc Nu
- Ngày sinh: cần đưa về dạng chuẩn dd/mm/yyyy
- Địa chỉ: xâu ký tự độ dài không quá 100
 
Viết chương trình nhập danh sách khách hàng từ file văn bản KHACHHANG.in, sắp xếp theo ngày sinh từ già nhất đến trẻ nhất. Không có hai khách hàng nào cùng ngày sinh.

**Input- file KHACHHANG.in**

Dòng đầu ghi số N là số khách hàng (không quá 20).

Tiếp theo là thông tin của N khách hàng, mỗi khách hàng ghi trên 4 dòng theo đúng thứ tự đã mô tả (không có mã)

**Output**

Danh sách khách hàng với đầy đủ các thông tin liệt kê ở trên, trong đó tên và ngày sinh đã được chuẩn hóa.

**Ví dụ**

 | **KHACHHANG.in** | **Output** |
|---|---|
| 2    nGuyen VAN nAm    Nam    12/12/1997    Mo Lao-Ha Dong-Ha Noi    TRan vAn biNh    Nam    14/11/1995    Phung Khoang-Nam Tu Liem-Ha Noi | KH002 Tran Van Binh Nam Phung Khoang-Nam Tu Liem-Ha Noi 14/11/1995    KH001 Nguyen Van Nam Nam Mo Lao-Ha Dong-Ha Noi 12/12/1997 |

### J07027 - QUẢN LÝ BÀI TẬP NHÓM

Lớp học LTHĐT được chia thành các nhóm. Mỗi nhóm sẽ đăng ký một bài tập. Hãy liệt kê toàn bộ danh sách sinh viên theo thứ tự sắp xếp mã sinh viên tăng dần và thứ tự nhóm, tên bài tập nhóm mà từng sinh viên cần thực hiện.

**Input – 3 file văn bản**

**SINHVIEN.in**

Dòng đầu ghi số N là số sinh viên

Mỗi sinh viên ghi 3 dòng gồm:

- Mã sinh viên: không quá 15 ký tự
- Họ tên: Không quá 50 ký tự
- Số điện thoại: không quá 15 ký tự số
 
**BAITAP.in**

Dòng đầu ghi số M là số bài tập.

Tiếp theo là M dòng, mỗi dòng ghi tên một bài tập lớn ứng với thứ tự nhóm từ 1 đến M. Độ dài tên bài tập không quá 200 ký tự.

**NHOM.in**

Có đúng N dòng, mỗi dòng ghi mã sinh viên và số thứ tự bài tập nhóm.

**Output**

Ghi ra danh sách tất cả sinh viên theo thứ tự mã sinh viên tăng dần (thứ tự từ điển). Mỗi sinh viên bao gồm: mã, họ tên, số điện thoại, số thứ tự nhóm, tên bài tập nhóm.

**Ví dụ**

 | **Input (3 file văn bản)** |
|---|
| **SINHVIEN.in**  5  B17DTCN001  Nguyen Chi Linh  0987345543  B17DTCN011  Vu Viet Thang  0981234567  B17DTCN023  Pham Trong Thang  0992123456  B17DTCN022  Nguyen Van Quyet  0977865432  B17DTCN031  Ngo Thanh Vien  0912313111  **BAITAP.in**  2  Xay dung website ban dien thoai truc tuyen  Xay dung ung dung quan ly benh nhan Covid-19  **NHOM.in**  B17DTCN001 1  B17DTCN011 1  B17DTCN023 1  B17DTCN022 2  B17DTCN031 2 |
| **Output** |
| B17DTCN001 Nguyen Chi Linh 0987345543 1 Xay dung website ban dien thoai truc tuyen  B17DTCN011 Vu Viet Thang 0981234567 1 Xay dung website ban dien thoai truc tuyen  B17DTCN022 Nguyen Van Quyet 0977865432 2 Xay dung ung dung quan ly benh nhan Covid-19  B17DTCN023 Pham Trong Thang 0992123456 1 Xay dung website ban dien thoai truc tuyen  B17DTCN031 Ngo Thanh Vien 0912313111 2 Xay dung ung dung quan ly benh nhan Covid-19 |

### J07028 - TÍNH GIỜ CHUẨN

Tại trường đại học ABC, môn học có mã môn và tên môn, thông tin của mỗi giảng viên gồm mã giảng viên, tên giảng viên.

Một giảng viên khi tham gia giảng dạy một môn học sẽ được ghi nhận số giờ chuẩn. Giả sử với mỗi môn học thì một giảng viên chỉ giảng dạy nhiều nhất 1 lớp học phần.

Viết chương trình lập bảng tính toán giờ chuẩn cho từng giảng viên.

**Input – 3 file văn bản**

**File MONHOC.in**

Dòng đầu ghi số môn học. Mỗi môn học viết trên một dòng gồm mã môn, sau đó đến khoảng trống rồi đến tên môn.

**File GIANGVIEN.in**

Dòng đầu ghi số giảng viên. Mỗi giảng viên viết trên một dòng gồm mã giảng viên và tên giảng viên.

**File GIOCHUAN.in**

Dòng đầu ghi số lớp học phần. Mỗi lớp học phần sẽ ghi trên một dòng gồm mã giảng viên, mã môn sau đó đến giờ chuẩn (dạng số thực).

**Output**

Ghi ra danh sách giảng viên theo thứ tự nhập và tổng giờ chuẩn tính được. Thông tin cần liệt kê chỉ bao gồm tên giảng viên và tổng số giờ chuẩn (viết chính xác đến 2 số phần thập phân).

**Ví dụ**

 | **Input – 3 file văn bản** | **Output** |
|---|---|
| **MONHOC.in**  2  INT1155 Tin hoc co so 2  INT1306 Cau truc du lieu va giai thuat  **GIANGVIEN.in**  2  GV01 Nguyen Van An  GV02 Hoang Binh Minh  **GIOCHUAN.in**  2  GV01 INT1155 113.2  GV02 INT1306 126.72 | Nguyen Van An 113.20  Hoang Binh Minh 126.72 |

### J07029 - SỐ NGUYÊN TỐ LỚN NHẤT TRONG FILE

Cho file nhị phân DATA.in trong đó ghi một ArrayList&lt;Integer&gt; gồm tối đa 100000 số nguyên, các số đều nguyên dương và không quá 106.

Hãy tìm **10 số** nguyên tố lớn nhất trong file và số lần xuất hiện của các số đó. Liệt kê 10 số theo thứ tự giảm dần.

**Input**

File nhị phân DATA.in. Đảm bảo có nhiều hơn 10 số nguyên tố khác nhau.

**Output**

Số 10 nguyên tố lớn nhất và số lần xuất hiện, mỗi số trên một dòng.

**Ví dụ**

 | **DATA.in** | **Output** |
|---|---|
| File nhị phân có một ArrayList&lt;Integer&gt; | Ghi 10 số nguyên tố lớn nhất và số lần  Ví dụ:  997 19  29 6  23 41  19 13  17 17  13 88  11 230  7 49  5 169  3 1321 |

### J07030 - CẶP SỐ NGUYÊN TỐ TRONG FILE - 1

Cho hai file nhị phân DATA1.in và DATA2.in trong đó ghi một ArrayList&lt;Integer&gt; gồm tối đa 100000 số nguyên, các số đều nguyên dương và không quá 106.

Hãy tìm các cặp số (n, m) sao cho:

- n &lt; m và cả hai đều là số nguyên tố
- n có xuất hiện trong file DATA1.in.
- m có xuất hiện trong file DATA2.in
- n + m = 1000000
 
Các cặp số tìm được cần liệt kê theo thứ tự tăng dần của giá trị n và không lặp lại.

**Input**

File nhị phân DATA1.in và DATA2.in

**Output**

Các cặp số thỏa mãn theo thứ tự tăng dần của n.

**Ví dụ**

 | **DATA1.in và DATA2.in** | **Output** |
|---|---|
| File nhị phân có một ArrayList&lt;Integer&gt; | Ghi các cặp số thỏa mãn.  Ví dụ:  227 999773  22643 977357  25583 974417 |

### J07031 - CẶP SỐ NGUYÊN TỐ TRONG FILE 2

Cho hai file nhị phân DATA1.in và DATA2.in trong đó ghi một ArrayList&lt;Integer&gt; gồm tối đa 100000 số nguyên, các số đều nguyên dương và không quá 106.

Hãy tìm các cặp số (n, m) sao cho:

- n &lt; m và cả hai đều là số nguyên tố
- n và m có xuất hiện trong file DATA1.in.
- n và m không xuất hiện trong file DATA2.in
- n + m = 1000000
 
Các cặp số tìm được cần liệt kê theo thứ tự tăng dần của giá trị n và không lặp lại.

**Input**

File nhị phân DATA1.in và DATA2.in

**Output**

Các cặp số thỏa mãn theo thứ tự tăng dần của n .

**Ví dụ**

 | **DATA1.in và DATA2.in** | **Output** |
|---|---|
| File nhị phân có một ArrayList&lt;Integer&gt; | Ghi các cặp số thỏa mãn.  Ví dụ:  227 999773  22643 977357  25583 974417 |

### J07032 - SỐ THUẬN NGHỊCH TRONG FILE

Cho hai file nhị phân DATA1.in và DATA2.in trong đó ghi một ArrayList&lt;Integer&gt; gồm tối đa 106 số nguyên, các số đều nguyên dương và không quá 106.

Viết chương trình liệt kê các số thuận nghịch thỏa mãn tất cả các điều kiện sau:

- Xuất hiện trong cả hai file DATA1.in và DATA2.in
- Tất cả các chữ số đều lẻ
- Số chữ số cũng là một số lẻ nhưng lớn hơn 1
 
Vì trong file có thể có rất nhiều số thỏa mãn nên người ta chỉ muốn liệt kê tối đa 10 số đầu tiên thỏa mãn các điều kiện trên theo thứ tự tăng dần. Kết quả cần liệt kê số đó kèm theo tổng số lần xuất hiện của số đó trong hai file cộng lại.

**Input**

File nhị phân DATA1.in và DATA2.in

**Output**

Các số thỏa mãn kèm theo tổng số lần xuất hiện trong cả hai file.

**Ví dụ**

 | **DATA1.in và DATA2.in** | **Output** |
|---|---|
| File nhị phân có một ArrayList&lt;Integer&gt; | Ghi tối đa 10 số thỏa mãn theo thứ tự tăng dần.  Ví dụ:  939 7  11311 12 |

### J07034 - DANH SÁCH MÔN HỌC

Thông tin về mỗi môn học bao gồm:

- Mã môn (không quá 10 ký tự)
- Tên môn (không quá 100 ký tự)
- Số tín chỉ: giá trị số nguyên dương không quá 6.
 
Viết chương trình nhập danh sách môn học và in ra danh sách đã sắp xếp theo tên môn (thứ tự từ điển).

**Input – file MONHOC.in**

Dòng đầu ghi số N là số môn học. Mỗi môn học ghi trên 3 dòng lần lượt là mã, tên và số tín chỉ

**Output**

Ghi ra danh sách đã sắp xếp theo tên môn, mỗi môn trên một dòng. Các thông tin cách nhau một khoảng trống.

**Ví dụ**

 | **MONHOC.in** | **Output** |
|---|---|
| 2  INT1155  Tin hoc co so 2  2  SKD1103  Ky nang tao lap Van ban  1 | SKD1103 Ky nang tao lap Van ban 1  INT1155 Tin hoc co so 2 2 |

### J07035 - BẢNG ĐIỂM THEO MÔN HỌC

Thông tin về môn học gồm:

- Mã môn (không quá 10 ký tự)
- Tên môn (không quá 100 ký tự)
- Số tín chỉ: giá trị số nguyên dương không quá 6.
 
Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100, có thể chưa ở dạng chuẩn
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 30)
 
Hãy nhập danh sách sinh viên (chú ý chuẩn hóa tên), danh sách môn học. Sau đó nhập điểm thi và hiển thị bảng điểm theo môn học.

Thứ tự hiển thị theo điểm giảm dần, nếu điểm bằng nhau thì sắp xếp theo mã sinh viên (thứ tự từ điển tăng dần).

**Input – 3 file văn bản**

**SINHVIEN.in**

Dòng đầu ghi số sinh viên (không quá 1000)

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

**MONHOC.in**

Dòng đầu ghi số số môn học. Mỗi môn học ghi trên 3 dòng lần lượt là mã, tên và số tín chỉ

**BANGDIEM.in**

Dòng đầu ghi số dòng của bảng điểm

Mỗi dòng tiếp theo gồm 3 thông tin: mã sinh viên, mã môn và điểm (số thực trong phạm vi 10).

Tiếp theo là một dòng ghi số N là số môn học cần liệt kê

Sau đó là N dòng ghi mã môn tương ứng

**Output**

Ghi ra bảng điểm của từng môn theo mẫu như trong ví dụ. Đảm bảo thứ tự sắp xếp theo yêu cầu đề bài.

Ví dụ

 | **Input** | **Output** |
|---|---|
| **SINHVIEN.in**  2  B15DCKT150  NGUYEN NGOC SON  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  NguyeN TrONg Tung  D15CQKT02-B  sv4@stu.ptit.edu.vn  **MONHOC.in**  2  INT1155  Tin hoc co so 2  2  SKD1103  Ky nang tao lap Van ban  1  **BANGDIEM.in**  2  B15DCKT150 INT1155 8.5  B15DCKT199 INT1155 9  1  INT1155 | BANG DIEM MON Tin hoc co so 2:  B15DCKT199 Nguyen Trong Tung D15CQKT02-B 9  B15DCKT150 Nguyen Ngoc Son D15CQKT02-B 8.5 |

### J07036 - BẢNG ĐIỂM THEO LỚP

Thông tin về môn học gồm:

- Mã môn (không quá 10 ký tự)
- Tên môn (không quá 100 ký tự)
- Số tín chỉ: giá trị số nguyên dương không quá 6.
 
Thông tin về mỗi sinh viên gồm:

- Mã sinh viên: dãy ký tự không có khoảng trống (không quá 15). Đảm bảo không trùng nhau.
- Họ và tên: độ dài không quá 100, có thể chưa ở dạng chuẩn
- Lớp: dãy ký tự không có khoảng trống (không quá 15)
- Email: dãy ký tự không có khoảng trống (không quá 30)
 
Hãy nhập điểm thi và hiển thị bảng điểm theo lớp. Với mỗi lớp, bảng điểm cần được liệt kê theo thứ tự mã môn học, sau đó đến mã sinh viên tăng dần.

**Input – 3 file văn bản**

**SINHVIEN.in**

Dòng đầu ghi số sinh viên (không quá 1000)

Mỗi sinh viên ghi trên 4 dòng lần lượt là: mã, họ tên, lớp, email.

**MONHOC.in**

Dòng đầu ghi số số môn học. Mỗi môn học ghi trên 3 dòng lần lượt là mã, tên và số tín chỉ

**BANGDIEM.in**

Dòng đầu ghi số dòng của bảng điểm

Mỗi dòng tiếp theo gồm 3 thông tin: mã sinh viên, mã môn và điểm (số thực trong phạm vi 10).

Tiếp theo là một dòng ghi số N là số lớp liệt kê bảng điểm

Sau đó là N dòng ghi lớp tương ứng

**Output**

Ghi ra bảng điểm của từng lớp theo mẫu như trong ví dụ. Các thông tin cần liệt kê gồm: mã sinh viên, tên sinh viên, mã môn, tên môn và điểm.

Đảm bảo thứ tự sắp xếp theo yêu cầu đề bài.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| **SINHVIEN.in**  2  B15DCKT150  NGUYEN NGOC SON  D15CQKT02-B  sv3@stu.ptit.edu.vn  B15DCKT199  NguyeN TrONg Tung  D15CQKT02-B  sv4@stu.ptit.edu.vn  **MONHOC.in**  2  INT1155  Tin hoc co so 2  2  SKD1103  Ky nang tao lap Van ban  1  **BANGDIEM.in**  2  B15DCKT150 INT1155 8.5  B15DCKT150 SKD1103 9  1  D15CQKT02-B | BANG DIEM lop D15CQKT02-B:  B15DCKT150 Nguyen Ngoc Son INT1155 Tin hoc co so 2 8.5  B15DCKT150 Nguyen Ngoc Son SKD1103 Ky nang tao lap Van ban 9 |

### J07037 - DANH SÁCH DOANH NGHIỆP

Để chuẩn bị cho đợt thực tập tốt nghiệp của sinh viên năm cuối, Khoa CNTT1 trao đổi với các doanh nghiệp đối tác và chốt số lượng sinh viên có thể nhận thực tập.

Hãy đọc danh sách doanh nghiệp từ file và hiển thị danh sách theo thứ tự mã tăng dần (thứ tự từ điển).

**Input – DN.in**

Dòng đầu ghi số doanh nghiệp.

Mỗi doanh nghiệp ghi trên 3 dòng:

- Mã doanh nghiệp (xâu ký tự không có dấu cách, độ dài không quá 10)
- Tên doanh nghiệp (xâu ký tự độ dài không quá 150)
- Số sinh viên có thể nhận: giá trị nguyên không quá 1000
 
**Output**

Ghi ra danh sách được sắp xếp theo mã tăng dần, mỗi thông tin ghi trên một dòng.

**Ví dụ**

 | **Input – DN.in** |
|---|
| 4  VIETTEL  TAP DOAN VIEN THONG QUAN DOI VIETTEL  40  FSOFT  CONG TY TNHH PHAN MEM FPT - FPT SOFTWARE  300  VNPT  TAP DOAN BUU CHINH VIEN THONG VIET NAM  200  SUN  SUN\*  50 |
| **Output** |
| FSOFT CONG TY TNHH PHAN MEM FPT - FPT SOFTWARE 300  SUN SUN\* 50  VIETTEL TAP DOAN VIEN THONG QUAN DOI VIETTEL 40  VNPT TAP DOAN BUU CHINH VIEN THONG VIET NAM 200 |

### J07040 - LIỆT KÊ THEO THỨ TỰ XUẤT HIỆN

Cho file nhị phân NHIPHAN.in chứa một ArrayList&lt;String&gt;. Mỗi String trong danh sách có thể có nhiều từ.

Cho file văn bản VANBAN.in có tối đa 200 dòng văn bản.

Hãy liệt kê các từ khác nhau xuất hiện trong cả hai file theo thứ tự xuất hiện trong file VANBAN.in.

**Input**

Hai file NHIPHAN.in và VANBAN.in theo mô tả.

**Output**

Danh sách các từ khác nhau xuất hiện trong cả hai file theo thứ tự xuất hiện trong file VANBAN.in. Mỗi từ trên một dòng.

*Chú ý: Tất cả các từ đều phải chuyển về dạng chữ viết thường.*

### J07041 - LIỆT KÊ CẶP SỐ - 1

Cho lớp Pair ghép cặp 2 số nguyên được mô tả như trong hình:

![Alt text](./img/J07041_1.png)

File dữ liệu nhị phân DATA.in có ghi một ArrayList&lt;Pair&gt; với các giá trị trong các cặp số là các số nguyên dương ngẫu nhiên, không quá 105.

Viết chương trình liệt kê các Pair thỏa mãn:

- Số thứ nhất phải nhỏ hơn số thứ hai
- Không trùng với bất cứ cặp nào trước đó.
- Các Pair được liệt kê theo thứ tự tăng dần, mỗi Pair một dòng theo mẫu
 
(first, second)

*Chú ý: giữa dấu phẩy và số thứ 2 có đúng một khoảng trống*

**Input**

File nhị phân DATA.in

**Output**

Ghi ra các cặp số thỏa mãn theo thứ tự tăng dần.

### J07042 - LIỆT KÊ CẶP SỐ - 2

Cho lớp Pair ghép cặp 2 số nguyên được mô tả như trong hình:

![Alt text](./img/J07042_1.png)

File dữ liệu nhị phân DATA.in có ghi một ArrayList&lt;Pair&gt; với giá trị nguyên dương ngẫu nhiên, không quá 105.

Viết chương trình liệt kê các Pair thỏa mãn:

- Số thứ nhất phải nhỏ hơn số thứ hai
- Không trùng với bất cứ cặp nào trước đó.
- Hai phần tử của cặp số thỏa mãn tính chất nguyên tố cùng nhau
- Các Pair được liệt kê theo thứ tự tăng dần, mỗi Pair một dòng theo mẫu
 
(first, second)

*Chú ý: giữa dấu phẩy và số thứ 2 có đúng một khoảng trống*

**Input**

File nhị phân DATA.in

**Output**

Ghi ra các cặp số thỏa mãn theo thứ tự tăng dần.

### J07045 - LOẠI PHÒNG

Khách sạn ABC có nhiều loại phòng khác nhau, mỗi loại phòng có các thông tin:

- Ký hiệu loại phòng (là một chữ cái viết hoa)
- Tên loại phòng: dãy ký tự viết hoa, không có khoảng trống
- Đơn giá ngày
- Phí phục vụ
 
Viết chương trình khai báo lớp LoaiPhong và đọc thông tin danh sách từ file PHONG.in sau đó in ra màn hình theo thứ tự sắp xếp theo tên.

**Input – file PHONG.in**

Dòng đầu ghi số loại phòng.

Mỗi loại ghi trên một dòng với lần lượt các thông tin ký hiệu, tên, đơn giá, phí phục vụ. Mỗi thông tin cách nhau một khoảng trống.

**Output**

Ghi ra danh sách đã sắp xếp theo tên, mỗi loại phòng ghi trên một dòng.

**Ví dụ**

 | **Input – PHONG.in** | **Output** |
|---|---|
| 2  C THUONG 150 0.03  B VIP 200 0.05 | C THUONG 150 0.03  B VIP 200 0.05 |

### J07046 - DANH SÁCH LƯU TRÚ

Khách sạn ABC lưu thông tin về các khách hàng đến lưu trú gồm các thông tin sau:

- Mã khách hàng, tự động tăng tính từ KH01
- Họ và tên
- Mã phòng (dãy ký tự)
- Ngày đến
- Ngày đi
 
Hãy nhập thông tin lưu trú từ file KHACH.in và sắp xếp theo số ngày lưu trú giảm dần.

Dữ liệu đảm bảo không có hai khách hàng nào có cùng số ngày lưu trú.

**Input – KHACH.in**

Dòng đầu ghi số lượng khách hàng

Mỗi khách hàng ghi trên 4 dòng gồm: họ tên, mã phòng, ngày đến, ngày đi.

**Output**

Ghi ra danh sách khách hàng sắp xếp theo thứ tự số ngày lưu trú giảm dần.

Các thông tin cần liệt kê gồm:

- Mã khách hàng
- Họ tên
- Mã phòng
- Số ngày lưu trú
 
*Chú ý: nếu ngày đến và đi là bằng nhau thì số ngày lưu trú bằng 0*

**Ví dụ**

 | **Input – KHACH.in** | **Output** |
|---|---|
| 2  Nguyen Van Hoang  55B1  01/01/2021  05/01/2021  Nguyen Trung Dung  04C6  01/01/2021  10/01/2021 | KH02 Nguyen Trung Dung 04C6 9  KH01 Nguyen Van Hoang 55B1 4 |

### J07047 - QUẢN LÝ KHÁCH SẠN

Khách sạn ABC có nhiều loại phòng khác nhau, mỗi loại phòng có các thông tin:

- Ký hiệu loại phòng (là một chữ cái viết hoa)
- Tên loại phòng: dãy ký tự viết hoa, không có khoảng trống
- Đơn giá ngày
- Phí phục vụ
 
Thông tin về các khách hàng đến lưu trú gồm các thông tin sau:

- Mã khách hàng, tự động tăng tính từ KH01
- Họ và tên
- Mã phòng (dãy ký tự)
- Ngày đến
- Ngày đi
 
Hãy nhập thông tin về phòng và khách lưu trú từ file DATA.in và tính toán tiền phải trả cho mỗi khách hàng.

Các thông tin liên quan đến tính giá tiền phải trả:

- Ký tự thứ 3 trong mã phòng chính là ký hiệu của loại phòng tương ứng
- Phí phục vụ của mỗi loại phòng được tính nhân với số tiền phòng đã tính theo đơn giá ngày và được cộng dồn vào số tiền phải trả.
- Các phòng có thể được giảm giá theo quy tắc: 
    - Nếu số ngày &lt; 10: không giảm
    - Nếu số ngày từ 10 đến dưới 20: giảm 2%
    - Nếu số ngày từ 20 đến dưới 30: giảm 4%
    - Nếu số ngày lớn hơn 30: giảm 6%
- Khách lưu trú ở chưa đến một ngày cũng cần được tính giá tiền phòng tương dương với 1 ngày.
- Sau khi tính toán, giá tiền phải trả cần làm tròn và in ra với hai chữ số phần thập phân.
 
**Input – DATA.in**

Dòng đầu ghi số loại phòng.

Mỗi loại ghi trên một dòng với lần lượt các thông tin ký hiệu, tên, đơn giá, phí phục vụ. Mỗi thông tin cách nhau một khoảng trống.

Tiếp theo là một dòng ghi số lượng khách hàng

Mỗi khách hàng ghi trên 4 dòng gồm: họ tên, mã phòng, ngày đến, ngày đi.

**Output**

Ghi ra thông tin trên mỗi dòng gồm:

- Mã khách hàng
- Tên khách hàng
- Mã phòng
- Số ngày lưu trú
- Tiền phải trả
 
Danh sách được sắp xếp theo số ngày lưu trú giảm dần. Dữ liệu đảm bảo không có hai khách hàng nào có cùng số ngày lưu trú.

**Ví dụ**

 | **Input – DATA.in** | **Output** |
|---|---|
| 2  C THUONG 150 0.03  B VIP 200 0.05  2  Nguyen Van Hoang  55B1  01/01/2021  05/01/2021  Nguyen Trung Dung  04C6  01/01/2021  10/01/2021 | KH02 Nguyen Trung Dung 04C6 9 1390.50  KH01 Nguyen Van Hoang 55B1 4 840.00 |

### J07048 - DANH SÁCH SẢN PHẨM – 2

Cửa hàng bán sản phẩm điện máy, công cụ cơ khí mô tả thông tin mỗi sản phẩm gồm các thông tin:

- Mã sản phẩm
- Tên sản phẩm
- Giá bán (USD)
- Thời hạn bảo hành (tính theo tháng).
 
Hãy nhập thông tin sản phẩm và in danh sách sắp xếp theo giá bán giảm dần. Nếu giá bán bằng nhau thì sắp theo mã sản phẩm (thứ tự từ điển)

**Input – file SANPHAM.in**

Dòng đầu ghi số sản phẩm.

Mỗi sản phẩm ghi trên 4 dòng lần lượt là mã, tên, giá bán, thời hạn.

**Output**

Ghi ra danh sách sắp xếp theo yêu cầu. Mỗi sản phẩm ghi trên một dòng với đầy đủ: mã, tên, giá bán, thời hạn.

**Ví dụ**

 | **Input – file SANPHAM.in** | **Output** |
|---|---|
| 2  KC740  May khoan KC1  39  18  KC742  May cat KC2  46  12 | KC742 May cat KC2 46 12  KC740 May khoan KC1 39 18 |

### J07049 - TÍNH NGÀY HẾT HẠN BẢO HÀNH

Cửa hàng bán sản phẩm điện máy, công cụ cơ khí mô tả thông tin mỗi sản phẩm gồm các thông tin:

- Mã sản phẩm
- Tên sản phẩm
- Giá bán (USD)
- Thời hạn bảo hành (tính theo tháng).
 
Thông tin về khách hàng gồm:

- Mã khách hàng (tự động tăng, tính từ KH01)
- Họ tên khách hàng
- Địa chỉ
- Mã sản phẩm
- Số lượng mua
- Ngày mua (định dạng dd/mm/yyyy)
 
Hãy tính ngày hết hạn bảo hành và in kết quả danh sách ra màn hình.

**Input – file MUAHANG.in**

Dòng đầu ghi số sản phẩm.

Mỗi sản phẩm ghi trên 4 dòng lần lượt là mã, tên, giá bán, thời hạn.

Tiếp theo là một dòng ghi số khách hàng.

Mỗi khách hàng ghi trên 5 dòng lần lượt là: họ tên khách hàng, địa chỉ, mã sản phẩm, số lượng mua, ngày mua.

**Output**

Ghi ra danh sách mua hàng đã xác định ngày hết hạn bảo hành. Thông tin cần được sắp xếp theo ngày hết hạn bảo hành tăng dần (tức là sản phẩm nào hết hạn trước thì liệt kê trước). Nếu bằng nhau thì sắp xếp theo mã khách hàng (thứ tự từ điển).

Các thông tin cần liệt kê:

- Mã khách hàng
- Tên khách hàng
- Địa chỉ
- Mã sản phẩm
- Tống số tiền cần thanh toán
- Ngày hết hạn bảo hành (định dạng dd/mm/yyyy)
 
**Ví dụ**

 | **Input – file MUAHANG.in** | **Output** |
|---|---|
| 2  KC740  May khoan KC1  39  18  KC742  May cat KC2  46  12  2  Le Ngoc Long  Hoang Mai  KC740  11  21/05/2009  Nguyen Sao Mai  Hoan Kiem  KC742  17  06/02/2009 | KH02 Nguyen Sao Mai Hoan Kiem KC742 782 06/02/2010  KH01 Le Ngoc Long Hoang Mai KC740 429 21/11/2010 |

### J07050 - SẮP XẾP MẶT HÀNG

Thông tin mặt hàng được mô tả gồm các thông tin:

- Mã hàng: tự động tăng, tính từ MH01
- Tên hàng: xâu ký tự độ dài không quá 100
- Nhóm hàng: xâu ký tự độ dài không quá 50
- Giá mua: số thực
- Giá bán: số thực
 
Hãy nhập thông tin khách hàng từ file văn bản MATHANG.in sắp xếp theo lợi nhuận giảm dần.

**Input - MATHANG.in**

Dòng đầu chứa số mặt hàng. Mỗi mặt hàng viết trên 4 dòng: Dòng 1: Tên mặt hàng. Dòng 2: Nhóm hàng. Dòng 3: Giá mua. Dòng 4: Giá bán

**Output**

Ghi ra danh sách mặt hàng đã sắp xếp theo lợi nhuận giảm dần (lợi nhuận tính bằng giá bán trừ đi giá mua).

Mỗi mặt hàng viết trên một dòng gồm: mã, tên, nhóm hàng và lợi nhuận (với 2 chữ số sau dấu phẩy).

Các thông tin cách nhau đúng 1 khoảng trống.

**Ví dụ:**

 | **Input - MATHANG.in** | **Output** |
|---|---|
| 3  May tinh SONY VAIO  Dien tu  16400  17699  Tu lanh Side by Side  Dien lanh  18300  25999  Banh Chocopie  Tieu dung  27.5    37 | MH02 Tu lanh Side by Side Dien lanh 7699.00  MH01 May tinh SONY VAIO Dien tu 1299.00  MH03 Banh Chocopie Tieu dung 9.50 |

### J07051 - TÍNH TIỀN PHÒNG

Khách sạn XYZ có đơn giá (theo ngày) được quy định khác nhau theo từng tầng. Khách hàng đến thuê phòng sẽ được tính tổng số tiền ở theo đơn giá cộng thêm chi phí dịch vụ phát sinh nếu có.

![Alt text](./img/J07051_1.png)

Hãy giúp khách sạn tính tiền phải trả cho từng khách hàng và sắp xếp theo thứ tự tổng tiền giảm dần.

**Input - file KHACHHANG.in**

Dòng đầu ghi số khách hàng (không quá 50)

Mỗi khách hàng ghi trên 4 dòng gồm:

- Tên khách hàng (xâu ký tự độ dài không quá 100, có thể chưa chuẩn)
- Số phòng
- Ngày nhận phòng (có thể chưa đúng định dạng dd/mm/yyyy)
- Ngày trả phòng (có thể chưa đúng định dạng dd/mm/yyyy)
- Tiền dịch vụ phát sinh (số nguyên dương nhỏ hơn 100)
 
**Output**

Ghi ra danh sách đã được sắp xếp theo tổng tiền giảm dần bao gồm lần lượt các thông tin:

- Mã khách hàng (tự động tăng theo thứ tự nhập, tính từ KH01)
- Tên khách hàng - đã được chuẩn hóa
- Số phòng
- Số ngày ở
- Thành tiền
 
**Ví dụ**

 | **Input - KHACHHANG.in** | **Output** |
|---|---|
| 3  Huynh VAN Thanh  103  5/6/2010  5/6/2010  15  le DUC cong  106  08/3/2010  1/5/2010  220  Tran Thi Bich Tuyen  207  10/4/2010  21/4/2010  96 | KH02 Le Duc Cong 106 55 1595  KH03 Tran Thi Bich Tuyen 207 12 504  KH01 Huynh Van Thanh 103 1 40 |

### J07052 - DANH SÁCH TRÚNG TUYỂN

Trường Đại học XYZ tuyển sinh theo hình thức xét điểm thi ba môn Toán – Lý – Hóa, trong đó điểm Toán được nhân đôi. Để đơn giản, khu vực tuyển sinh được quy định luôn bởi ba chữ cái đầu tiên trong mã thí sinh. Do rất thích các thí sinh đến từ Khu vực 3 nên trường XYZ tự quy định giá trị điểm ưu tiên Khu vực như trong bảng sau:

![Alt text](./img/J07052_1.png)

Cho trước số chỉ tiêu. Hãy xác định mức điểm chuẩn và kết quả của từng thí sinh sau đó sắp xếp theo điểm xét tuyển giảm dần. Chú ý: tất cả thí sinh bằng điểm chuẩn trở lên đều được coi là trúng tuyển, kể cả khi số thí sinh trúng tuyển nhiều hơn chỉ tiêu.

**Input - file THISINH.in**

Dòng đầu tiên ghi số thí sinh (nhỏ hơn 100), thông tin của một thí sinh trên 5 dòng lần lượt là:

- Mã thí sinh
- Họ tên - có thể chưa ở dạng chuẩn
- Điểm toán
- Điểm lý
- Điểm hóa
 
Các giá trị điểm đều đảm bảo trong phạm vi \[0,10\] và có thể có 1 chữ số phần thập phân.

Dòng cuối ghi giá trị số chỉ tiêu.

**Output**

Dòng đầu tiên ghi ra giá trị điểm chuẩn xác định được (có 1 chữ số phần thập phân)

Tiếp theo in ra danh sách đã sắp xếp theo điểm xét tuyển giảm dần, nếu điểm xét tuyển bằng nhau thì sắp xếp theo mã thí sinh (thứ tự từ điển) .

Với mỗi thí sinh ghi ra các thông tin:

- Mã thí sinh
- Họ tên - đã được chuẩn hóa
- Điểm ưu tiên (có thể có 1 số phần thập phân)
- Điểm xét tuyển – có ưu tiên (có thể có 1 số phần thập phân)
- Trạng thái: TRUNG TUYEN hoac TRUOT (sau khi đã tính cả điểm ưu tiên)
 
**Ví dụ**

 | **Input - THISINH.in** | **Output** |
|---|---|
| 2  KV2A002  Hoang THAnh tuan  5  6  5  KV3B123   LY Thi THU ha  8  6.5  7  1 | 32.0  KV3B123 Ly Thi Thu Ha 2.5 32 TRUNG TUYEN  KV2A002 Hoang Thanh Tuan 1 22 TRUOT |

### J07053 - XÉT TUYỂN

Công ty PH tổ chức bài thi tuyển dụng gồm 2 nội dung: thi lý thuyết và thi thực hành. Điểm để xếp loại sẽ là điểm trung bình của hai bài thi đó cộng với điểm thưởng và làm tròn (round) đến hàng đơn vị. (Chú ý nếu tổng lớn hơn 10 thì vẫn chỉ là 10).

Điểm thưởng được tính như sau:

- Nếu không có điểm nào nhỏ hơn 8 thì điểm thưởng = 1
- Nếu không có điểm nào nhỏ hơn 7.5 thì điểm thưởng = 0.5
- Còn lại: không có điểm thưởng.
 
Xếp loại theo quy tắc sau:

- Nhỏ hơn 5: Truot
- Từ 5 đến 6: Trung binh
- Điểm 7: Kha
- Điểm 8: Gioi
- Điểm 9 hoặc 10: Xuat sac
 
Hãy nhập thông tin và lập bảng kết quả xếp loại.

**Input - file XETTUYEN.in**

Dòng đầu ghi số người thi tuyển (nhỏ hơn 100).

Mỗi người sẽ có thông tin trên 4 dòng gồm:

- Họ tên - có thể chưa được chuẩn hóa
- Ngày sinh (có thể chưa đúng định dạng dd/mm/yyyy)
- Điểm lý thuyết
- Điểm thực hành
 
Các giá trị điểm đảm bảo trong phạm vi 10 và có thể có 1 số phần thập phân.

**Output**

Ghi ra danh sách theo đúng thứ tự nhập, các thông tin cách nhau một khoảng trống, lần lượt là:

- Mã thi tuyển (bắt đầu từ PH01)
- Họ tên: đã được chuẩn hóa
- Tuổi (chỉ cần tính theo năm sinh)
- Điểm trung bình (đã tính cả điểm thưởng và làm tròn)
- Xếp loại
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  Doan Thi Kim  13/03/1982  8  9.5  dinh Thi NGOC HA  3/9/1996  6.5  8   tran thanh mai  12/9/2004  8  9 | PH01 Doan Thi Kim 39 10 Xuat sac  PH02 Dinh Thi Ngoc Ha 25 7 Kha  PH03 Tran Thanh Mai 17 10 Xuat sac |

### J07054 - TÍNH ĐIỂM TRUNG BÌNH

Nhóm sinh viên PTIT cùng nhau đăng ký 3 môn học trong Học kỳ hè năm 2021 theo đúng thứ tự:

- Môn 1: Lập trình hướng đối tượng: 3 tín chỉ
- Môn 2: Ngôn ngữ lập trình C++: 3 tín chỉ
- Môn 3: Tin học cơ sở 2: 2 tín chỉ
 
Người ta muốn xếp hạng thứ tự các sinh viên trong danh sách theo điểm trung bình giảm dần. Biết rằng điểm trung bình tính đến 2 số phần thập phân và nếu điểm bằng nhau thì thứ hạng cũng bằng nhau.

**Input – BANGDIEM.in**

Dòng đầu ghi số sinh viên (không quá 20).

Mỗi sinh viên ghi trên 4 dòng gồm:

- Họ tên: có thể chưa được chuẩn hóa
- Điểm môn 1
- Điểm môn 2
- Điểm môn 3
 
Các giá trị điểm là số nguyên và đảm bảo trong phạm vi từ 0 đến 10.

**Output**

Ghi ra danh sách sinh viên đã tính điểm và sắp xếp theo xếp hạng từ cao nhất đến thấp nhất, gồm các thông tin:

- Mã sinh viên (tự động tăng theo thứ tự nhập, tính từ SV01)
- Họ tên đã chuẩn hóa
- Điểm trung bình với đúng 2 số phần thập phân
- Xếp hạng
 
Chú ý: 2 sinh viên có điểm trung bình bằng nhau thì xếp hạng bằng nhau, và nếu có 2 sinh viên hạng là X thì sinh viên tiếp theo trong danh sách có hạng X+2.

Trong trường hợp xếp hạng bằng nhau thì cần sắp xếp theo mã sinh viên tăng dần.

**Ví dụ**

 | **Input – BANGDIEM.in** | **Output** |
|---|---|
| 2   ha Thi kieu anh  7  6  7  Pham THI HAO  6  7  6 | SV01 Ha Thi Kieu Anh 6.63 1  SV02 Pham Thi Hao 6.38 2 |

### J07055 - XẾP LOẠI

Điểm tổng kết môn Lập trình hướng đối tượng được tính theo thang điểm 10 với tỉ lệ như sau:

- Điểm luyện tập: chiếm 25%
- Điểm thực hành online: chiếm 35%
- Điểm thi: chiếm 40%
 
Hãy nhập bảng điểm, tính điểm tổng kết và xếp loại cho các sinh viên theo quy tắc:

- Từ 8 trở lên: xếp loại GIOI
- Từ 6.5 đến dưới 8: xếp loại KHA
- Từ 5 đến dưới 6.5: xếp loại TRUNG BINH
- Dưới 5 thì xếp loai KEM
 
**Input – BANGDIEM.in**

Dòng đầu ghi số sinh viên (không quá 20).

Mỗi sinh viên ghi trên 4 dòng gồm:

- Họ tên: có thể chưa được chuẩn hóa
- Điểm luyện tập
- Điểm thực hành
- Điểm thi
 
Các giá trị điểm là số nguyên và đảm bảo trong phạm vi từ 0 đến 10.

**Output**

Ghi ra danh sách sinh viên đã tính điểm và **sắp xếp theo điểm tổng kết** từ cao xuống thấp, gồm các thông tin:

- Mã sinh viên (tự động tăng theo thứ tự nhập, tính từ SV01)
- Họ tên đã chuẩn hóa
- Điểm tổng kết với đúng 2 số phần thập phân
- Xếp loại
 
Chú ý: Dữ liệu đảm bảo không có 2 sinh viên nào có điểm tổng kết bằng nhau.

**Ví dụ**

 | **Input – BANGDIEM.in** | **Output** |
|---|---|
| 2   ha Thi kieu anh  7  6  7  Pham THI HAO  6  7  6 | SV01 Ha Thi Kieu Anh 6.65 KHA  SV02 Pham Thi Hao 6.35 TRUNG BINH |

### J07056 - TÍNH TIỀN ĐIỆN

Các hộ gia đình trong thành phố X được chia thành 3 loại A, B, C với định mức sử dụng điện như sau:

- Loại A: Định mức 100 kWh
- Loại B: Định mức 500 kWh
- Loại C: Định mức 200 kWh
 
Hãy tính toán số tiền phải thanh toán theo quy tắc:

**Tính tiền trong định mức:**

Nếu số điện (Số cuối - Số đầu) nhỏ hơn định mức thì bằng số điện \* 450 Nếu số điện &gt; định mức thì bằng định mức \*450

**Tiền vượt định mức**

Nếu số điện &gt; định mức thì bằng (số điện - định mức) \*1000 Nếu không thì bằng 0

**Thuế VAT** = 5% số tiền vượt định mức

Số tiền phải nộp = Tiền trong định mức + Tiền vượt định mức + Thuế VAT

**Input – file KHACHHANG.in**

Dòng đầu ghi số khách hàng.

Mỗi khách hàng ghi trên 2 dòng:

- Họ tên: có thể chưa chuẩn hóa
- Loại hộ gia đình, chỉ số đầu, chỉ số cuối. Mỗi thông tin cách nhau một khoảng trống.
 
**Output**

Ghi ra danh sách đã sắp xếp theo tổng số tiền phải trả giảm dần gồm các thông tin:

- Mã khách hàng: tính từ KH01 theo thứ tự nhập
- Họ tên đã chuẩn hóa
- Tiền trong định mức
- Tiền vượt định mức
- Tổng số tiền phải nộp.
 
Dữ liệu đảm bảo không có hai hộ gia đình nào có cùng số tiền nộp bằng nhau.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2   nGuyEn Hong Ngat  C 200 278   Chu thi minh  A 120 160 | KH01 Nguyen Hong Ngat 35100 0 0 35100  KH02 Chu Thi Minh 18000 0 0 18000 |

### J07057 - ĐIỂM TUYỂN SINH

Theo quy định mới, điểm tuyển sinh vào trường đại học XYZ sau khi tính tổng sẽ được cộng ưu tiên, cụ thể:

- Thí sinh khu vực 1 ưu tiên 1.5 điểm
- Thí sinh khu vực 2 ưu tiên 1 điểm
- Thí sinh khu vực 3 không ưu tiên
- Thí sinh dân tộc Kinh không ưu tiên
- Thí sinh các dân tộc khác ưu tiên 1.5 điểm
 
Hãy tính tổng điểm đã ưu tiên và xác định tình trạng trúng tuyển. Biết điểm chuẩn của trường năm nay là 20.5 điểm.

**Input – THISINH.in**

Dòng đầu ghi số thí sinh.

Mỗi thí sinh ghi trên 4 dòng gồm:

- Họ tên: có thể chưa chuẩn hóa
- Điểm thi: giá trị số thực không quá 30
- Dân tộc
- Khu vực
 
**Output**

Ghi ra danh sách đã sắp xếp theo tổng điểm (đã tính ưu tiên) giảm dần, nếu tổng điểm bằng nhau thì sắp xếp theo mã thí sinh tăng dần. Các thông tin cần liệt kê gồm:

- Mã thí sinh (tính theo thứ tự nhập từ TS01)
- Họ tên đã chuẩn hóa
- Tổng điểm với đúng 1 chữ số phần thập phân
- Trạng thái: Do hoặc Truot
 
**Ví dụ**

 | **Input – THISINH.in** | **Output** |
|---|---|
| 2  Nguyen hong ngat  22  Kinh  1   Chu thi MINh  14  Dao  3 | TS01 Nguyen Hong Ngat 23.5 Do  TS02 Chu Thi Minh 15.5 Truot |

### J07059 - DANH SÁCH CA THI

Học viện Hoàng gia tổ chức thi thời kỳ giãn cách theo các hình thức thi linh hoạt, phù hợp với từng môn học.

Mỗi ca thi gồm các thông tin:

- Mã ca thi: tự động tăng, tính từ C001
- Ngày thi: đúng định dạng dd/mm/yyyy
- Giờ thi: theo đúng định dạng hh:mm
- Phòng thi: một dãy chữ số đại diện cho ID phòng online, không quá 12 chữ số
 
Hãy nhập danh sách các ca thi và sắp xếp theo thời gian thi (từ sớm nhất đến muộn nhất). Nếu hai ca thi cùng giờ thì sắp xếp theo mã ca thi tăng dần.

**Input – file văn bản CATHI.in**

Dòng đầu ghi số ca thi. Mỗi ca thi ghi trên 3 dòng gồm Ngày, Giờ và ID phòng thi.

**Output**

Ghi ra danh sách các ca thi theo thứ tự thời gian, nếu cùng giờ thì sắp xếp theo mã ca thi.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  09/01/2022    15:30    70172  09/01/2022    10:00    70279 | C002 09/01/2022 10:00 70279  C001 09/01/2022 15:30 70172 |

### J07060 - SẮP XẾP LỊCH THI

Học viện Hoàng gia tổ chức thi thời kỳ giãn cách theo các hình thức thi linh hoạt, phù hợp với từng môn học.

Thông tin về mỗi môn học gồm:

- Mã môn: xâu ký tự không có khoảng trống, không quá 15 ký tự
- Tên môn: xâu ký tự không có thể có khoảng trống, không quá 100 ký tự
- Hình thức thi: xâu ký tự không có thể có khoảng trống, không quá 100 ký tự
 
Mỗi ca thi gồm các thông tin:

- Mã ca thi: tự động tăng, tính từ C001
- Ngày thi: đúng định dạng dd/mm/yyyy
- Giờ thi: theo đúng định dạng hh:mm
- Phòng thi: một dãy chữ số đại diện cho ID phòng online, không quá 12 chữ số
 
Lịch thi được xây dựng dựa trên mã môn và mã ca thi và mã nhóm lớp. Theo quy định, nhóm lớp đơn giản là các giá trị chữ số, bắt đầu từ 01 và không quá 99. Mỗi nhóm sẽ có số sinh viên tham gia ca thi đó.

Hãy nhập lịch thi và sắp xếp lại theo thứ tự thời gian. Nếu cùng giờ thì sắp theo mã ca thi (thứ tự từ điển).

Input – gồm 3 file văn bản.

**MONTHI.in**

Dòng đầu ghi số môn học. Mỗi môn ghi trên 3 dòng lần lượt là mã môn, tên môn, hình thức thi.

**CATHI.in**

Dòng đầu ghi số ca thi. Mỗi ca thi ghi trên 3 dòng gồm Ngày, Giờ và ID phòng thi.

**LICHTHI.in**

Dòng đầu ghi số lượng các dòng trong lịch thi.

Mỗi dòng tiếp theo ghi 4 thông tin: mã ca thi, mã môn, mã nhóm, số sinh viên. Mỗi thông tin cách nhau một khoảng trống.

**Output**

Ghi ra danh sách lịch thi đã sắp xếp theo yêu cầu, các thông tin cần liệt kê gồm:

- Ngày thi
- Giờ thi
- ID Phòng thi
- Tên môn
- Nhóm
- Số sinh viên
 
Các thông tin liệt kê cách nhau đúng một khoảng trống

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| **MONTHI.in**  2  MUL1320  Nhap mon da phuong tien  Bai tap lon + Van dap truc tuyen  BAS1203  Giai tich 1  Thi viet + Van dap truc tuyen | 09/01/2022 10:00 70279 Giai tich 1 04 72  09/01/2022 15:30 70172 Nhap mon da phuong tien 01 46 |
| **CATHI.in**  2  09/01/2022    15:30    70172  09/01/2022    10:00    70279 |
| **LICHTHI.in**  2  C001 MUL1320 01 46  C002 BAS1203 04 72 |

### J07071 - TÊN VIẾT TẮT

Không hiểu sao khi comment trên các trang mạng xã hội, các bạn trẻ rất hay có thói quen viết tắt tên của “đối tượng”. Quy tắc viết tắt được nhắc đến trong bài tập này là lấy chữ cái đầu của mỗi từ và thêm dấu chấm vào giữa (không có khoảng trống).

Ví dụ:

- Nguyễn Văn Nam sẽ được viết tắt thành N.V.N
- Hoàng Trung Dũng sẽ được viết tắt thành H.T.D
 
Đôi khi để tăng tính tò mò của người đọc, tên viết tắt còn có thể thêm một ký tự dấu \* thay cho một trong các ký tự viết tắt. Ví dụ N.V.\* hoặc H.\*.D (chú ý: chỉ viết nhiều nhất một dấu \* và dấu \* cũng chỉ thay cho đúng 1 ký tự viết tắt).

Cho một danh sách họ tên trong file văn bản DANHSACH.in

Các xâu đều là Tiếng Việt không dấu và đảm bảo đã được chuẩn hóa đúng quy tắc. Tuy nhiên chưa được sắp xếp theo tên.

Với mỗi từ viết tắt, hãy in ra danh sách các họ tên có thể đúng với viết tắt đó theo thứ tự từ điển (sắp xếp theo tên, nếu tên giống nhau thì sắp xếp theo họ).

**Input – file văn bản DANHSACH.in**

Dòng đầu tiên ghi số N là số lượng họ tên. Tiếp theo là N dòng họ tên, các xâu họ tên có độ dài không quá 50.

Tiếp theo là một dòng ghi số M là số lượng từ viết tắt. Sau đó là M dòng, mỗi dòng một từ viết tắt

**Output**

Ghi ra M danh sách các họ tên phù hợp với M từ viết tắt tương ứng. Yêu cầu sắp xếp mỗi danh sách theo thứ tự từ điển (sắp xếp theo tên, nếu tên giống nhau thì sắp xếp theo họ).

**Ví dụ**

 | **Input – DANHSACH.in** | **Output** |
|---|---|
| 4  Nguyen Manh Son  Ngo Minh Tuan  Nguyen Manh Hung  Tran Trung Dung  1  N.M.\* | Nguyen Manh Hung  Nguyen Manh Son  Ngo Minh Tuan |

### J07072 - CHUẨN HÓA VÀ SẮP XẾP

Cho một danh sách họ tên trong file văn bản DANHSACH.in

Các xâu đều là Tiếng Việt không dấu nhưng có thể chưa được chuẩn hóa.

Hãy chuẩn hóa họ tên theo đúng quy tắc viết tên thông thường: chữ cái đầu mỗi từ viết hoa, các chữ cái sau viết thường, giữa 2 từ có đúng một khoảng trống.

Sau đó in ra màn hình danh sách đã được sắp xếp theo tên (thứ tự từ điển). Nếu trùng tên thì sắp xếp theo họ rồi đến tên đệm.

Chú ý: tên theo quy tắc Tiếng Việt là từ cuối cùng trong xâu họ tên.

**Input – file văn bản DANHSACH.in**

Có không quá 200 xâu họ tên, độ dài mỗi xâu không quá 100.

Chú ý: không có số dòng. Cần đọc đến hết file.

**Output**

Ghi ra danh sách đã chuẩn hóa và sắp xếp theo thứ tự từ điển (sắp xếp theo tên, nếu tên giống nhau thì sắp xếp theo họ rồi đến tên đệm).

**Ví dụ**

 | **Input – DANHSACH.in** | **Output** |
|---|---|
| nguyEn ManH son   ngo MINH tuAn   nguyen manh hung  TRAN TRUNG DUNG | Tran Trung Dung  Nguyen Manh Hung  Nguyen Manh Son  Ngo Minh Tuan |

### J07073 - ĐĂNG KÝ HÌNH THỨC GIẢNG DẠY

Chuẩn bị cho học kỳ thời và để thích ứng linh hoạt với tình hình dịch bệnh, Học viện Hoàng gia dự kiến cho phép các Khoa và Bộ môn được phép đăng ký hình thức giảng dạy linh hoạt cho các môn học. Thông tin về mỗi môn học khi đăng ký gồm:

- Mã môn học: xâu ký tự, độ dài không quá 20
- Tên môn học: xâu ký tự, độ dài không quá 100
- Số tín chỉ: giá trị số nguyên từ 1 đến 10
- Hình thức giảng dạy lý thuyết: có thể là “Truc tiep” hoặc “Truc tuyen”
- Hình thức giảng dạy thực hành: có thể là:
    - “Truc tiep”
    - “Truc tuyen” hoặc ghi rõ một địa chỉ tên miền online có đoạn cuối là .ptit.edu.vn (ví dụ code.ptit.edu.vn …)
 
Hãy nhập danh sách đăng ký môn học và lọc ra danh sách các môn học đăng ký thực hành trực tuyến. Sau đó sắp xếp theo mã môn học (thứ tự từ điển tăng dần)

**Input – file văn bản MONHOC.in**

Dòng đầu ghi số môn học. Mỗi môn học ghi trên 5 dòng lần lượt là: mã môn, tên môn, số tín chỉ, hình thức học lý thuyết, hình thức học thực hành.

Output

Ghi ra danh sách các môn thực hành trực tuyến đã sắp xếp theo mã.

Các thông tin cần liệt kê gồm: mã môn, tên môn, số tín chỉ, hình thức lý thuyết, hình thức thực hành. Mỗi thông tin cách nhau một khoảng trống.

Ví dụ

 | **Input – MONHOC.in** | **Output** |
|---|---|
| 3  INT1306  Cau truc du lieu va giai thuat  3  Truc tiep  code.ptit.edu.vn  INT13110  Lap trinh mang voi C++  3  Truc tiep  Truc tuyen  INT1155  Tin hoc co so 2  2  Truc tiep  code.ptit.edu.vn | INT1155 Tin hoc co so 2 2 Truc tiep code.ptit.edu.vn  INT1306 Cau truc du lieu va giai thuat 3 Truc tiep code.ptit.edu.vn  INT13110 Lap trinh mang voi C++ 3 Truc tiep Truc tuyen |

### J07074 - LỊCH GIẢNG DẠY THEO MÔN HỌC

Để chuẩn bị tổ chức giảng dạy học kỳ mới, Học viện Hoàng gia phân công giảng viên cho từng nhóm lớp với lịch giảng dạy cố định cho từng nhóm.

Thông tin về môn học gồm:

- Mã môn
- Tên môn
- Số tín chỉ
 
Thông tin về nhóm lớp học phần bao gồm:

- Mã nhóm (tự động tăng tính từ HP001)
- Mã môn
- Ngày giảng dạy (thứ trong tuần – đánh số từ 2 đến 7, không có Chủ Nhật).
- Kíp học: giá trị số từ 1 đến 6
- Họ tên giảng viên
- Phòng học
 
Hãy viết chương trình nhập thông tin lịch giảng dạy từ file văn bản, sau đó lọc ra lịch giảng dạy theo môn học và sắp xếp theo thời gian giảng dạy, từ đầu tuần đến cuối tuần.

**Input – 2 file văn bản**

**MONHOC.in**

Dòng đầu ghi số môn học. Mỗi môn học ghi trên 3 dòng gồm mã môn, tên môn, số tín chỉ.

**LICHGD.in**

Dòng đầu ghi số nhóm lớp học phần. Mỗi nhóm gồm các thông tin:

- Mã môn
- Thứ
- Kíp
- Họ tên giảng viên
- Phòng học
 
Mỗi thông tin ghi trên một dòng

Dòng cuối cùng ghi mã môn học cần liệt kê danh sách.

**Output – in ra màn hình**

Ghi ra danh sách nhóm lớp của môn học được yêu cầu. Trình bày theo mẫu như trong ví dụ trong đó mỗi nhóm lớp sẽ có các thông tin: mã nhóm, thứ, kíp, giảng viên, phòng học.

Sắp xếp theo thời gian giảng dạy, từ đầu tuần đến cuối tuần. Nếu cùng kíp học thì sắp xếp theo họ tên giảng viên (thứ tự từ điển).

**Ví dụ**

 | **Input – 2 file văn bản** |
|---|
| **MONHOC.in**  2  INT1155  Tin hoc co so 2  2  INT13162  Lap trinh voi Python  3  **LICHGD.in**  4  INT13162  5  1  Nguyen Hoang Anh  102-A2  INT1155  3  1  Nguyen Dinh Hien  201A-A3  INT1155  4  1  Nguyen Quy Sy  201A-A3  INT1155  5  1  Tran Quy Nam  201A-A3  INT1155 |
| **Output** |
| LICH GIANG DAY MON Tin hoc co so 2:  HP002 3 1 Nguyen Dinh Hien 201A-A3  HP003 4 1 Nguyen Quy Sy 201A-A3  HP004 5 1 Tran Quy Nam 201A-A3 |

### J07075 - LỊCH GIẢNG DẠY THEO GIẢNG VIÊN

Để chuẩn bị tổ chức giảng dạy học kỳ mới, Học viện Hoàng gia phân công giảng viên cho từng nhóm lớp với lịch giảng dạy cố định cho từng nhóm.

Thông tin về môn học gồm:

- Mã môn
- Tên môn
- Số tín chỉ
 
Thông tin về nhóm lớp học phần bao gồm:

- Mã nhóm (tự động tăng tính từ HP001)
- Mã môn
- Ngày giảng dạy (thứ trong tuần – đánh số từ 2 đến 7, không có Chủ Nhật).
- Kíp học: giá trị số từ 1 đến 6
- Họ tên giảng viên
- Phòng học
 
Hãy viết chương trình nhập thông tin lịch giảng dạy từ file văn bản, sau đó lọc ra lịch giảng dạy của một giảng viên và sắp xếp theo thời gian giảng dạy, từ đầu tuần đến cuối tuần.

**Input – 2 file văn bản**

**MONHOC.in**

Dòng đầu ghi số môn học. Mỗi môn học ghi trên 3 dòng gồm mã môn, tên môn, số tín chỉ.

**LICHGD.in**

Dòng đầu ghi số nhóm lớp học phần. Mỗi nhóm gồm các thông tin:

- Mã môn
- Thứ
- Kíp
- Họ tên giảng viên
- Phòng học
 
Mỗi thông tin ghi trên một dòng

Dòng cuối cùng ghi họ tên giảng viên cần liệt kê danh sách.

Dữ liệu đảm bảo họ tên giảng viên đều đã được chuẩn hóa và có tồn tại trong lịch giảng dạy.

**Output – in ra màn hình**

Ghi ra lịch giảng dạy của giảng viên được yêu cầu. Trình bày theo mẫu như trong ví dụ, trong đó mỗi dòng gồm các thông tin: mã nhóm, tên môn, thứ, kíp, phòng học.

Sắp xếp theo thời gian giảng dạy, từ đầu tuần đến cuối tuần. Nếu cùng kíp học thì sắp xếp theo họ tên giảng viên (thứ tự từ điển).

Ví dụ

 | **Input – 2 file văn bản** |
|---|
| **MONHOC.in**  2  INT1449  Phat trien ung dung cho cac thiet bi di dong  3  INT13162  Lap trinh voi Python  3  **LICHGD.in**  3  INT13162  5  4  Nguyen Trong Khanh  102-A2  INT1449  2  2  Nguyen Hoang Anh  105-A2  INT13162  5  1  Nguyen Hoang Anh  102-A2  Nguyen Hoang Anh |
| **Output** |
| LICH GIANG DAY GIANG VIEN Nguyen Hoang Anh:  HP002 Phat trien ung dung cho cac thiet bi di dong 2 2 105-A2  HP003 Lap trinh voi Python 5 1 102-A2 |

### J07076 - SẮP XẾP MA TRẬN

Cho ma trận A có kích thước N\*M chỉ bao gồm các số nguyên có giá trị tuyệt đối không quá 10000. Hãy sắp xếp cột thứ **i** của ma trận theo thứ tự từ nhỏ đến lớn và in kết quả ra màn hình.

Chú ý: thứ tự cột sẽ tính từ 1 đến M

**Input – file văn bản MATRIX.in**

Dòng đầu ghi số bộ test (không quá 20).

Mỗi bộ test viết trên 2 dòng:

- Dòng đầu ghi 3 số N, M, i
- Dòng thứ 2 ghi các số trong ma trận lần lượt từ hàng 1 đến hàng N. Các số cách nhau một khoảng trống
 
Các ràng buộc: 2 ≤ N, M ≤ 100; 1 ≤ i ≤ M; 0 ≤ ∣A\[I,j\] ∣ ≤ 10000)

**Output – in ra màn hình**

Với mỗi bộ test, ghi ra N dòng của ma trận đã sắp xếp.

**Ví dụ**

 | **MATRIX.in** | **Output** |
|---|---|
| 1  2 2 1  90 49 85 88 | 85 49  90 88 |

### J07077 - TÍNH GIÁ TRỊ BIỂU THỨC

Cho biểu thức S với các toán tử +, -, \*, / và dấu ngoặc (). Các toán hạng là các số có giá trị không vượt quá 100. Hãy tính giá trị biểu thức S. Phép chia thực hiện với số nguyên, input đảm bảo số bị chia luôn khác 0, đáp số biểu thức có không quá 18 chữ số.

**Input – file văn bản BIEUTHUC.in:**

Dòng đầu tiên là số lượng bộ test (T &lt;= 100).

Mỗi dòng gồm một xâu S, không quá 100 kí tự. Các toán hạng là các số nguyên không âm.

**Output:**

Với mỗi test, in ra đáp án tìm được.

**Ví dụ:**

 | **BIEUTHUC.in** | **Output** |
|---|---|
| 4  6\*3+2-(6-4/2)  100+99\*22  6\*((4\*3)+5)  1-2 | 16  2278  102  -1 |

### J07078 - TÌM VỊ TRÍ XÂU CON

Cho xâu s1 và s2 chỉ gồm các chữ cái viết thường. Hãy tìm các vị trí xuất hiện của xâu s2 trong xâu s1.

**Input – file văn bản STRING.in:**

Dòng đầu ghi số bộ test (không quá 10)

Mỗi bộ test gồm 2 dòng. Dòng thứ nhất chứa xâu s1, dòng thứ 2 chứa xâu s2. Độ dài 2 xâu không vượt quá 106.

**Output:**

In ra lần lượt các vị trí xuất hiện của xâu s2 trong xâu s1. Chỉ số đánh dấu bắt đầu từ 1.

Nếu không tìm thấy thì không cần in ra gì cả.

**Ví dụ:**

 | **STRING.in** | **Output** |
|---|---|
| 2  aaaaa  aa  abcde  bc | 1 2 3 4  2 |

### J07081 - SẮP XẾP DANH SÁCH SINH VIÊN

Mỗi sinh viên có các thông tin:

- Mã sinh viên: dãy ký tự có độ dài không quá 15
- Họ tên: dãy ký tự đã chuẩn hóa, độ dài không quá 50
- Số ĐT: dãy ký tự số độ dài không quá 15
- Email: độ dài không quá 50
 
Viết chương trình nhập danh sách sinh viên file SINHVIEN.in sau đó sắp xếp theo tên (thứ tự từ điển) và in kết quả ra màn hình.

**Input – file văn bản SINHVIEN.in**

Dòng đầu ghi số sinh viên. Mỗi sinh viên ghi trên 4 dòng lần lượt là mã SV, họ tên, số ĐT, email.

**Output – ghi ra màn hình**

Ghi ra danh sách đã sắp xếp theo tên, nếu trùng tên thì sắp xếp theo họ rồi đến tên đệm Nếu tất cả họ và tên trùng nhau thì sắp xếp theo mã sinh viên (các tiêu chí sắp xếp đều theo thứ tự từ điển tăng dần).

Viết đầy đủ các thông tin mã, tên, điện thoại, emai, mỗi thông tin cách nhau một khoảng trống. Mỗi sinh viên trên một dòng.

Chú ý: trong Tiếng Việt, tên là từ cuối cùng trong xâu họ tên.

**Ví dụ**

 | **Input – file SINHVIEN.in** |
|---|
| 3  B19DCCN999  Ngo Quang Huy  0976544443  B19DCCN999@stu.ptit.edu.vn  B19DCCN998  Nguyen Le Tu  0345678999  B19DCCN998@stu.ptit.edu.vn  B19DCCN997  Nguyen Manh Cuong  0987654321  B19DCCN997@stu.ptit.edu.vn |
| **Output** |
| B19DCCN997 Nguyen Manh Cuong 0987654321 B19DCCN997@stu.ptit.edu.vn  B19DCCN999 Ngo Quang Huy 0976544443 B19DCCN999@stu.ptit.edu.vn  B19DCCN998 Nguyen Le Tu 0345678999 B19DCCN998@stu.ptit.edu.vn |

### J07084 - THỜI GIAN ONLINE LIÊN TỤC

Hết học kỳ nên rảnh rỗi, nhóm admin CODE PTIT thử thống kê xem trong học kỳ vừa qua sinh viên nào online liên tục lâu nhất trên hệ thống.

Thông tin về thời gian online dài nhất của cá nhân mỗi sinh viên được truy vấn từ CSDL sau đó mô tả với ba thông tin:

- Họ và tên sinh viên: xâu ký tự Tiếng Việt không dấu, độ dài không quá 50
- Thời gian bắt đầu: đúng định dạng: dd/mm/yyyy hh:mm:ss
- Thời gian kết thúc: đúng định dạng: dd/mm/yyyy hh:mm:ss
 
Hãy tính thời gian online của từng sinh viên và sắp xếp theo thứ tự thời gian giảm dần (từ lâu nhất đến ít nhất). Nếu hai sinh viên có thời gian online bằng nhau thì sắp xếp theo họ tên (thứ tự từ điển).

**Input**

File văn bản ONLINE.in

- Dòng đầu ghi số sinh viên
- Mỗi sinh viên ghi trên ba dòng lần lượt là họ tên (đã chuẩn hóa), thời gian bắt đầu, thời gian kết thúc.
 
**Output**

Ghi ra danh sách sắp xếp theo thời gian online giảm dần.

Mỗi dòng ghi họ tên và thời lượng online (tính theo phút)

**Ví dụ**

 | **Input – ONLINE.in** | **Output** |
|---|---|
| 3  Do Viet Anh  11/12/2021 16:35:00  11/12/2021 17:35:00  Le Tuan Anh  11/12/2021 16:45:00  11/12/2021 18:15:00  Nguyen Tuan Anh  11/12/2021 17:00:00  11/12/2021 19:15:00 | Nguyen Tuan Anh 135  Le Tuan Anh 90  Do Viet Anh 60 |

### J07085 - TỔNG CHỮ SỐ

Cho file nhị phân DATA.in trong đó ghi một ArrayList&lt;String&gt; theo kiểu Object, với không quá 1000 String, mỗi String là một dãy ký tự độ dài không quá 200, chỉ có các ký tự chữ cái và chữ số.

Với mỗi xâu ký tự trong danh sách, hãy tách ra các chữ số và ghép lại thành một số nguyên dương. Sau đó tính tổng chữ số của số đó.

*Chú ý: các chữ số 0 nếu có ở đầu số nguyên dương tạo được thì cần được bỏ đi khi in ra.*

**Input – file nhị phân DATA.in**

Gồm một ArrayList&lt;String&gt; với mỗi String là một dãy chữ số.

**Output**

Ghi ra các số nguyên dương tạo được cho mỗi String trong danh sách và giá trị tổng chữ số tương ứng.

**Ví dụ**

 | **Input - file nhị phân DATA.in** | **Output** |
|---|---|
| *Gồm một ArrayList&lt;String&gt; với mỗi String là một dãy ký tự. Có thể ví dụ ở dạng ký tự như dưới đây:*  Jhsf00dklT12uhf780LPPZH  AAAAddd0000000000000000001T | 12780 18  1 1 |

## ỨNG DỤNG JAVA COLLECTION

### J08010 - TÌM TỪ THUẬN NGHỊCH DÀI NHẤT

Cho dữ liệu vào dạng văn bản. Hãy tìm ra từ thỏa mãn tính chất ***thuận nghịch có độ dài  
 lớn nhất*** trong file đó và cho biết từ đó ***xuất hiện bao nhiêu lần***. Nếu có nhiều từ cùng  
 có độ dài lớn nhất thì in ra tất cả các từ đó theo thứ tự xuất hiện trong file ban đầu.  
 **Input:** Không quá 1000 từ.  
 **Output**:

Ghi ra trên một dòng từ thuận nghịch có độ dài lớn nhất và số lần xuất hiện của  
 nó. Nếu có nhiều từ cùng có độ dài lớn nhất thì các từ được liệt kê theo thứ tự xuất  
 hiện ban đầu.  
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| AAA BAABA HDHDH ACBSD SRGTDH DDDDS    DUAHD AAA AD DA HDHDH AAA AAA AAA AAA    DDDAS HDHDH HDH AAA AAA AAA AAA AAA    AAA AAA AAA    DHKFKH DHDHDD HDHDHD DDDHHH HHHDDD    TDTD | HDHDH 3 |

### J08011 - LIỆT KÊ VÀ ĐẾM

Cho một dãy các số nguyên dương không quá 9 chữ số, mỗi số cách nhau vài khoảng trống, có thể xuống dòng. Hãy tìm các số không giảm (các chữ số theo thứ tự từ trái qua phải tạo thành dãy không giảm) và đếm số lần xuất hiện của các số đó.

**Input**: Gồm các số nguyên dương không quá 9 chữ số. Không quá 10000 số.

**Output:** Ghi ra các số không giảm kèm theo số lần xuất hiện. Các số được liệt kê theo thứ tự sắp xếp số lần xuất hiện giảm dần. Các số có số lần xuất hiện bằng nhau thì số nào xuất hiện trước in ra trước.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 123 321 23456 123 123 23456 3523 123 321 4567 8988 78 7654 9899 3456 123 678 999 78 3456 987654321 4546 63543 4656 13432 4563 123471 659837 454945 34355 9087 9977 98534 3456 23134 | 123 5  3456 3    23456 2    78 2    4567 1  678 1  999 1 |

### J08012 - HÌNH SAO

Một đơn đồ thị vô hướng được gọi là Hình Sao nếu có một đỉnh có thể nối đến tất cả các đỉnh còn lại, còn các đỉnh khác thì không có cạnh nối với nhau.

Cho mô tả một đơn đồ thị vô hướng N đỉnh với đúng N-1 cạnh. Hãy kiểm tra xem đồ thị đó có phải dạng Hình Sao hay không.

**Dữ liệu vào**

- Dòng đầu tiên ghi số N là số đỉnh của đồ thị (1 ≤ N ≤ 105).
- N-1 dòng tiếp theo, mỗi dòng ghi ra một cặp (u,v) là cạnh của đồ thị. Dữ liệu đảm bảo u ≠ v.
 
**Kết quả**

- Ghi ra trên một dòng chữ **“Yes”** nếu đồ thị là Hình Sao; chữ **“No”** trong trường hợp ngược lại.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5    1 2    1 3    1 4    1 5 | Yes |

### J08015 - CẶP SỐ CÓ TỔNG BẰNG K

Cho dãy số A\[\] gồm có N phần tử.

Nhiệm vụ của bạn là đếm xem có bao nhiêu cặp (i, j) mà A\[i\] + A\[j\] = K cho trước.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test gồm số nguyên N và K (1≤ N ≤ 100 000, 0 ≤ K ≤ 109).
- Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 1018).
 
**Output:**

Với mỗi test, in ra trên một dòng là đáp án thu được.

**Ví dụ:**

 | Input: | Output |
|---|---|
| 4  4 6  1 5 7 -1  5 6  1 5 7 -1 5  4 2  1 1 1 1  13 11  10 12 10 15 -1 7 6 5 4 2 1 1 1 | 2  3  6  9 |

### J08020 - KIỂM TRA DÃY NGOẶC ĐÚNG

Cho một xâu chỉ gồm các kí tự ‘(‘, ‘)’, ‘\[‘, ‘\]’, ‘{‘, ‘}’. Một dãy ngoặc đúng được định nghĩa như sau:

\- Xâu rỗng là 1 dãy ngoặc đúng.

\- Nếu A là 1 dãy ngoặc đúng thì (A), \[A\], {A} là 1 dãy ngoặc đúng.

\- Nếu A và B là 2 dãy ngoặc đúng thì AB là 1 dãy ngoặc đúng.

Cho một xâu S. Nhiệm vụ của bạn là xác định xâu S có là dãy ngoặc đúng hay không?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test gồm 1 xâu S có độ dài không vượt quá 100 000.

**Output:**

Với mỗi test, in ra “YES” nếu như S là dãy ngoặc đúng, in ra “NO” trong trường hợp ngược lại.

**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  \[()\]{}{\[()()\]()}  \[(\]) | YES  NO |

### J08021 - DÃY NGOẶC ĐÚNG DÀI NHẤT

Cho một xâu chỉ gồm các kí tự ‘(‘ và ‘)’. Một dãy ngoặc đúng được định nghĩa như sau:

\- Xâu rỗng là 1 dãy ngoặc đúng.

\- Nếu A là 1 dãy ngoặc đúng thì (A) là 1 dãy ngoặc đúng.

\- Nếu A và B là 2 dãy ngoặc đúng thì AB là 1 dãy ngoặc đúng.

Cho một xâu S. Nhiệm vụ của bạn là hãy tìm dãy ngoặc đúng dài nhất xuất hiện trong xâu đã cho.

**Input:** Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test gồm một xâu S có độ dài không vượt quá 105 kí tự.

**Output:** Với mỗi test in ra một số nguyên là độ dài dãy ngoặc đúng dài nhất tìm được.

**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 3  ((()  )()())  ()(())))) | 2  4  6 |

### J08022 - PHẦN TỬ BÊN PHẢI ĐẦU TIÊN LỚN HƠN

Cho dãy số A\[\] gồm N phần tử. Với mỗi A\[i\], bạn cần tìm phần tử bên phải đầu tiên lớn hơn nó. Nếu không tồn tại, in ra -1.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test bắt đầu bởi số nguyên N (1 ≤ N ≤ 100000).

Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 109).

**Output:**

Với mỗi test, in ra trên một dòng N số R\[i\], với R\[i\] là giá trị phần tử đầu tiên lớn hơn A\[i\].

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  4  4 5 2 25  3  2 2 2  4  4 4 5 5 | 5 25 25 -1  -1 -1 -1  5 5 -1 -1 |

 

Giới hạn thời gian: 2s

### J08023 - HÌNH CHỮ NHẬT LỚN NHẤT

Cho N cột, mỗi cột có chiều cao bằng H\[i\]. Bạn hãy tìm hình chữ nhật lớn nhất bị che phủ bởi các cột?

![Alt text](./img/J08023_1.png)

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test bắt đầu bởi số nguyên N (N ≤ 100 000).

Dòng tiếp theo gồm N số nguyên H\[i\] (1 ≤ H\[i\] ≤ 109).

**Output:**

Với mỗi test, in ra diện tích hình chữ nhật lớn nhất tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  7  6 2 5 4 5 1 6  3  2 2 2 | 12  6 |

### J08024 - SỐ 0 VÀ SỐ 9

Cho số tự nhiên N. Hãy tìm số nguyên dương X nhỏ nhất được tạo bởi số 9 và số 0 chia hết cho N. Ví dụ với N = 5 ta sẽ tìm ra X = 90.

**Input:**

- Dòng đầu tiên ghi lại số lượng test T (T≤100).
- Những dòng kế tiếp mỗi dòng ghi lại một test. Mỗi test là một số tự nhiên N được ghi trên một dòng (N≤100).
 
**Output:**

- Đưa ra theo từng dòng số X nhỏ nhất chia hết cho N tìm được .
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5  7 | 90  9009 |

Giới hạn thời gian: 2s

### J08025 - QUAY HÌNH VUÔNG

Có một chiếc bảng hình chữ nhật với 6 miếng ghép, trên mỗi miếng ghép được điền một số nguyên trong khoảng từ 1 đến 6. Tại mỗi bước, chọn một hình vuông (bên trái hoặc bên phải), rồi quay theo chiều kim đồng hồ.

 | ![Alt text](./img/J08025_1.png) | ![Alt text](./img/J08025_2.png) | ![Alt text](./img/J08025_3.png) |
|---|---|---|

Yêu cầu: Cho một trạng thái của bảng, hãy tính số phép biến đổi ít nhất để đưa bảng đến trạng thái đích.

**Input:**

- Dòng đầu ghi số bộ test (không quá 10). Mỗi bộ test gồm hai dòng:
    - Dòng đầu tiên chứa 6 số là trạng thái bảng ban đầu (thứ tự từ trái qua phải, dòng 1 tới dòng 2).
    - Dòng thứ hai chứa 6 số là trạng thái bảng đích (thứ tự từ trái qua phải, dòng 1 tới dòng 2).
 
**Output:**

- Với mỗi test, in ra một số nguyên là đáp số của bài toán.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  1 2 3 4 5 6  4 1 2 6 5 3 | 2 |

### J08026 - BIẾN ĐỔI S – T

Cho hai số nguyên dương S và T (S, T&lt;10000) và hai thao tác (a), (b) dưới đây:

**Thao tác (a)**: Trừ S đi 1 (S = S-1) ;

**Thao tác (b)**: Nhân S với 2 ( S = S\*2);

Hãy dịch chuyển S thành T sao cho số lần thực hiện các thao tác (a), (b) là ít nhất. Ví dụ với S =2, T=5 thì số các bước ít nhất để dịch chuyển S thành T thông qua 4 thao tác sau:

**Thao tác (a)**: 2\*2 = 4;

**Thao tác (b)**: 4-1 = 3;

**Thao tác (a)**: 3\*2 = 6;

**Thao tác (b)**: 6-1 = 5;

**Input:**

- Dòng đầu tiên ghi lại số tự nhiên T là số lượng Test;
- T dòng kế tiếp mỗi dòng ghi lại một bộ Test. Mỗi test là một bộ đôi S và T.
 
**Output:** Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  2 5  3 7  7 4 | 4  4  3 |

### J08027 - GÕ BÀN PHÍM

Trong quá trình gõ một dòng văn bản, chúng ta thường sử dụng phím sang trái, sang phải hoặc xóa lùi (backspace). Cho một dãy ký tự mô tả các thao tác gõ phím, trong đó:

- Ký tự ‘**-**’ mô tả phím backspace (xóa lùi). Ký tự ở phía trước con trỏ (nếu có) sẽ bị xóa.
- Ký tự ‘**&lt;**’ mô tả phím di chuyển sang trái. Con trỏ sẽ sang trái 1 ký tự nếu có thể.
- Ký tự ‘**&gt;**’ mô tả phím di chuyển sang phải. Con trỏ sẽ sang phải 1 ký tự nếu có thể.
- Các ký tự khác là các chữ cái Tiếng Anh (in hoa hoặc in thường). Bàn phím để ở chế độ Insert. Tức là nếu con trỏ không ở cuối dòng thì khi chèn các ký tự sẽ đẩy các ký tự khác sang phải một vị trí.
 
Hãy thử tính toán và viết ra kết quả tương ứng.

**Input**

Có một dòng không quá 106 ký tự mô tả dãy gõ bàn phím.

**Output**

Ghi ra kết quả.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| &lt;&lt;PI&lt;T&gt;&gt;Ta- | PTIT |

### J08028 - HÌNH CHỮ NHẬT ĐƠN SẮC

Cho bảng có kích thước M\*N các ô vuông đơn vị.

Với mỗi dãy số A có N phần tử và các giá trị A\[i\] thỏa mãn nguyên dương, không vượt quá M, người ta tiến hành tô các ô trong bảng như sau:

- Tô từ trên xuống dưới trong từng cột
- Với cột thứ i, đầu tiên tô A\[i\] ô màu vàng, tiếp theo là M – A\[i\] ô màu xanh.
 
Ví dụ dưới đây là bảng 5\*5 với A\[\] = {2, 1, 3, 4, 0}.

![Alt text](./img/J08028_1.png)

Hãy tính diện tích hình chữ nhật lớn nhất thỏa mãn:

- Cạnh hình chữ nhật song song với cạnh của bảng
- Tất cả các ô trong hình chữ nhật đều cùng màu.
 
**Input**

Dòng đầu tiên ghi hai số M và N (0 &lt; N,M &lt;=106 ).

Dòng thứ 2 ghi N số của dãy A thỏa mãn ràng buộc đề bài.

**Output**

Ghi ra giá trị diện tích tính được.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 9  1 3 4 4 5 4 4 3 1 | 21 |

### J08029 - QUÂN MÃ

Cho một quân mã trên bàn cờ vua tại vị trí ST. Nhiệm vụ của bạn là hãy tìm số bước di chuyển ít nhất để đưa quân mã tới vị trí EN.

![Alt text](./img/J08029_1.png)

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test gồm 2 xâu dạng “xy” và “uv”, trong đó x, y là kí tự trong “abcdefgh” còn y, v là số thuộc 1, 2, 3, 4, 5, 6, 7, 8.

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 8  e2 e4  a1 b2  b2 c3  a1 h8  a1 h7  h8 a1  b1 c3  f6 f6 | 2  4  2  6  5  6  1  0 |

### JKT013 - SỐ LỘC PHÁT

Một số được gọi là lộc phát nếu chỉ có 2 chữ số 6 và 8. Cho số tự nhiên N. Hãy liệt kê các số lộc phát có không quá N chữ số.

**Input:**

- Dòng đầu tiên ghi lại số tự nhiên T là số lượng bộ test (T&lt;10);
- T dòng kế tiếp mỗi dòng ghi số N (1&lt;N&lt;15).
 
**Output:**

- Dòng đầu tiên là số lượng số lộc phát tìm được. Dòng thứ hai in ra đáp án **theo thứ tự giảm dần**.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  2  3 | 6  88 86 68 66 8 6  14  888 886 868 866 688 686 668 666 88 86 68 66 8 6 |

### JKT014 - ĐẦU TƯ  CHỨNG KHOÁN

Bạn là một nhà đầu tư chứng khoán nổi tiếng. Nhiệm vụ hàng ngày của bạn là tính nhịp tăng giảm của phiên chứng khoán trong N ngày để có thể bắt kịp thị trường. Nhịp chứng khoán của ngày thứ i được định nghĩa là số ngày liên tiếp từ ngày thứ i trở về mà giá chứng khoán bé hơn hoặc bằng với giá chứng khoán của ngày i.

**Input:** Dòng đầu ghi số bộ test (không quá 10). Mỗi test có 2 dòng.

- Dòng đầu tiên gồm 1 số nguyên N (1 ≤ N ≤ 105) là số ngày.
- Dòng tiếp theo gồm N số nguyên A1, A2, …, AN (1 ≤ Ai ≤ 106) là giá chứng khoán của các ngày.
 
**Output**

- In ra N số B1, B2, …, BN trong đó Bi là nhịp chứng khoán của ngày thứ i.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  7  100 80 60 70 60 75 85 | 1 1 1 2 1 4 6 |

### JKT015 - GÕ BÀN PHÍM

Trong quá trình gõ một dòng văn bản, chúng ta thường sử dụng phím sang trái, sang phải hoặc xóa lùi (backspace). Cho một dãy ký tự mô tả các thao tác gõ phím, trong đó:

- Ký tự ‘**-**’ mô tả phím backspace (xóa lùi). Ký tự ở phía trước con trỏ (nếu có) sẽ bị xóa.
- Ký tự ‘**&lt;**’ mô tả phím di chuyển sang trái. Con trỏ sẽ sang trái 1 ký tự nếu có thể.
- Ký tự ‘**&gt;**’ mô tả phím di chuyển sang phải. Con trỏ sẽ sang phải 1 ký tự nếu có thể.
- Các ký tự khác là các chữ cái Tiếng Anh (in hoa hoặc in thường). Bàn phím để ở chế độ Insert. Tức là nếu con trỏ không ở cuối dòng thì khi chèn các ký tự sẽ đẩy các ký tự khác sang phải một vị trí.
 
Hãy thử tính toán và viết ra kết quả tương ứng.

**Input**

Có một dòng không quá 106 ký tự mô tả dãy gõ bàn phím.

**Output**

Ghi ra kết quả.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| &lt;&lt;PI&lt;T&gt;&gt;Ta- | PTIT |