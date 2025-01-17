# ĐỀ BÀI: THUẬT TOÁN NÂNG CAO - 2024

## DUYỆT ĐỒ THỊ

### 1179 - DFS TRÊN ĐỒ THỊ VÔ HƯỚNG

Cho đồ thị vô hướng G= được biểu diễn dưới dạng danh sách cạnh. Hãy viết thuật toán duyệt theo chiều sâu bắt đầu tại đỉnh uÎV (DFS(u)=?)

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm |E| +1 dòng: dòng đầu tiên đưa vào ba số |V|, |E| tương ứng với số đỉnh và số cạnh của đồ thị, và u là đỉnh xuất phát; |E| dòng tiếp theo đưa vào các bộ đôi uÎV, vÎV tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤200; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra danh sách các đỉnh được duyệt theo thuật toán DFS(u) của mỗi test theo khuôn dạng của ví dụ dưới đây.

 **Ví dụ:**

| Input: | Output: |
|---|---|
| 1  6 9 5  1 2  1 3  2 3  2 4  3 4  3 5  4 5  4 6  5 6 | 5 3 1 2 4 6 |

### 1181 - BFS TRÊN ĐỒ THỊ VÔ HƯỚNG

Cho đồ thị vô hướng G= được biểu diễn dưới dạng danh sách cạnh. Hãy viết thuật toán duyệt theo chiều rộng bắt đầu tại đỉnh uÎV (BFS(u)=?)

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào ba số |V|, |E|, uÎV tương ứng với số đỉnh, số cạnh và đỉnh bắt đầu duyệt; Dòng tiếp theo đưa vào các bộ đôi uÎV, vÎV tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤200; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra danh sách các đỉnh được duyệt theo thuật toán BFS(u) của mỗi test theo khuôn dạng của ví dụ dưới đây.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 1  6 9 1  1 2 1 3 2 3 2 5 3 4 3 5 4 5 4 6 5 6 | 1 2 3 5 4 6 |

### 1184 - TÌM ĐƯỜNG ĐI THEO DFS VỚI ĐỒ THỊ CÓ HƯỚNG

Cho đồ thị có hướng G= được biểu diễn dưới dạng danh sách cạnh. Hãy tìm đường đi từ đỉnh sÎV đến đỉnh tÎV trên đồ thị bằng thuật toán DFS.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào bốn số |V|, |E|, sÎV, tÎV tương ứng với số đỉnh, số cạnh, đỉnh u, đỉnh v; Dòng tiếp theo đưa vào các bộ đôi uÎV, vÎV tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra đường đi từ đỉnh s đến đỉnh t của mỗi test theo thuật toán DFS của mỗi test theo khuôn dạng của ví dụ dưới đây. Nếu không có đáp án, in ra -1.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 1  6 9 1 6  1 2 2 5 3 1 3 2 3 5 4 3 5 4 5 6 6 4 | 1 2 5 6 |

### 1187 - KIỂM TRA ĐƯỜNG ĐI

Cho đồ thị vô hướng có N đỉnh và M cạnh. Có Q truy vấn, mỗi truy vấn yêu cầu trả lời câu hỏi giữa 2 đỉnh x và y có tồn tại đường đi tới nhau hay không?

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test gồm 2 số nguyên N, M (1 ≤ N, M ≤ 1000).
- M dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v cho biết có cạnh nối giữa đỉnh u và v.
- Dòng tiếp là số lượng truy vấn Q (1 ≤ Q ≤ 1000).
- Q dòng tiếp theo, mỗi dòng gồm 2 số nguyên x và y.

**Output:** Với mỗi truy vấn, in ra “YES” nếu có đường đi từ x tới y, in ra “NO” nếu ngược lại.

**Ví dụ:**

| **Input:** | **Output** |
|---|---|
| 1  5 5  1 2  2 3  3 4  1 4  5 6  2  1 5  2 4 | NO  YES |

### 1192 - LIỆT KÊ ĐỈNH TRỤ

Cho đồ thị vô hướng liên thông G= được biểu diễn dưới dạng danh sách cạnh. Sử dụng thuật toán DFS hoặc BFS, hãy đưa ra tất cả các đỉnh trụ của đồ thị?

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào hai số |V|, |E| tương ứng với số đỉnh và số cạnh; Dòng tiếp theo đưa vào các bộ đôi uÎV, vÎV tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra danh sách các đỉnh trụ của mỗi test theo từng dòng.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 1  5 5  1 2 1 3 2 3 2 5 3 4 | 2 3 |

### 1194 - LIỆT KÊ CẠNH CẦU

Cho đồ thị vô hướng liên thông G= được biểu diễn dưới dạng danh sách cạnh. Sử dụng thuật toán DFS hoặc BFS, hãy đưa ra tất cả các cạnh cầu của đồ thị?

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào hai số |V|, |E| tương ứng với số đỉnh và số cạnh; Dòng tiếp theo đưa vào các bộ đôi uÎV, vÎV tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra danh sách các cạch cầu của mỗi test theo từng dòng. In ra đáp án theo thứ tự từ điển, theo dạng “a b …” với a &lt; b.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 1  5 5  1 2 1 3 2 3 2 5 3 4 | 2 5 3 4 |

### 1196 - KIỂM TRA CHU TRÌNH

Cho đồ thị vô hướng G= được biểu diễn dưới dạng danh sách cạnh. Sử dụng thuật toán DFS hoặc BFS, hãy kiểm tra xem đồ thị có tồn tại chu trình hay không?

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào hai số |V|, |E| tương ứng với số đỉnh, số cạnh của đồ thị; Dòng tiếp theo đưa vào các bộ đôi uÎV, vÎV tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra YES hoặc “NO” kết quả test theo từng dòng tương ứng với đồ thị tồn tại hoặc không tồn tại chu trình.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 1  6 9  1 2 1 3 2 3 2 5 3 4 3 5 4 5 4 6 5 6 | YES |

## CHƯA PHÂN LOẠI

### 1186 - TÌM ĐƯỜNG ĐI THEO BFS TRÊN ĐỒ THỊ CÓ HƯỚNG

Cho đồ thị có hướng G= được biểu diễn dưới dạng danh sách cạnh. Hãy tìm đường đi từ đỉnh uÎV đến đỉnh vÎV trên đồ thị bằng thuật toán BFS.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào bốn số |V|, |E|, sÎV, tÎV tương ứng với số đỉnh, số cạnh, đỉnh u, đỉnh v; |E| Dòng tiếp theo đưa vào các bộ đôi uÎV, vÎV tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;
 
**Output:**

- Đưa ra đường đi từ đỉnh s đến đỉnh t của mỗi test theo thuật toán BFS của mỗi test theo khuôn dạng của ví dụ dưới đây. Nếu không có đáp án, in ra -1.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 1  6 9 1 6  1 2 2 5 3 1 3 2 3 5 4 3 5 4 5 6 6 4 | 1 2 5 6 |

### S27 - SỐ LỚN NHẤT BẬC K

Cho hai số nguyên N và K, trong đó N không quá 107, K không quá 10.

Số lớn nhất bậc K của N được định nghĩa là giá trị lớn nhất có thể sau khi thực hiện nhiều nhất K lần các chữ số của N. Ví dụ K =3 và N = “1234567” ta số lớn nhất bậc K của N là “7654321”.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là số K; dòng tiếp theo là xâu ký tự S.
- T, K, S thỏa mãn ràng buộc: 1≤T≤100; 0≤K≤10; 1≤lengh(S)≤7.
 
**Output:**

- Đưa ra số lớn nhất bậc K của N trên một dòng.
 
 **Ví dụ:**

 | Input | Output |
|---|---|
| 3    4    1234567    3    3435335    2    1034 | 7654321    5543333    4301 |

## ĐỒ THỊ CƠ BẢN VÀ NÂNG CAO

### 1205 - TÔ MÀU ĐỒ THỊ

Một trong những bài toán kinh điển của lý thuyết đồ thị là bài toán Tô màu đồ thị. Bài toán được phát biểu như sau: Cho đồ thị vô hướng G = được biểu diễn dưới dạng danh sách cạnh và số M. Nhiệm vụ của bạn là kiểm tra xem đồ thị có thể tô màu các đỉnh bằng nhiều nhất M màu sao cho hai đỉnh kề nhau đều có màu khác nhau hay không?

![https://media.geeksforgeeks.org/wp-content/uploads/mcolor.png](https://media.geeksforgeeks.org/wp-content/uploads/mcolor.png)

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào ba số V, E, M tương ứng với số đỉnh, số cạnh và số màu; phần thứ hai đưa vào các cạnh của đồ thị.
- T, V, E, M thỏa mãn ràng buộc: 1≤T ≤100; 1≤V≤10; 1≤ E ≤N(N-1), 1≤V≤N.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    4 5 3    1 2  2 3  3 4  4 1  1 3    3 3 2    1 2  2 3  1 3 | YES    NO |

### 1206 - ĐƯỜNG ĐI HAMILTON

Đường đi đơn trên đồ thị có hướng hoặc vô hướng đi qua tất cả các đỉnh của đồ thị mỗi đỉnh đúng một lần được gọi là đường đi Hamilton. Cho đồ thị vô hướng G = , hãy kiểm tra xem đồ thị có đường đi Hamilton hay không?

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào hai số V, E tương ứng với số đỉnh, số cạnh của đồ thị; phần thứ hai đưa vào các cạnh của đồ thị.
- T, V, E thỏa mãn ràng buộc: 1≤T ≤100; 1≤V≤10; 1≤ E ≤15.

**Output:**

- Đưa ra 1 hoặc 0 tương ứng với test có hoặc không có đường đi Hamilton theo từng dòng.

 **Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    4 4    1 2 2 3 3 4 2 4    4 3    1 2 2 3 2 4 | 1  0 |

### 1207 - ĐỒ THỊ HAI PHÍA

Đồ thị hai phía là một đồ thị đặc biệt, trong đó tập các đỉnh có thể được chia thành hai tập không giao nhau thỏa mãn điều kiện không có cạnh nối hai đỉnh bất kỳ thuộc cùng một tập. Cho đồ thị N đỉnh và M cạnh, bạn hãy kiểm tra đồ thị đã cho có phải là một đồ thị hai phía hay không?

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi số nguyên N và M (1 ≤ N, M ≤ 1000).
- M dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v cho biết có cạnh nối giữa đỉnh u và v.

**Output:**

- Với mỗi test, in ra “YES” nếu đồ thị đã cho là một đồ thị hai phía, in ra “NO” trong trường hợp ngược lại.

**Ví dụ:**

| **Input:** | **Output** |
|---|---|
| 2  5 4  1 5  1 3  2 3  4 5  3 3  1 2  1 3  2 3 | YES  NO |

### 1209 - CHÚ CỪU XA CÁCH

Trên cánh đồng kích thước N x N có K chú cừu. Người nông dân sợ các chú cừu đi lạc nên đã làm một số rào chắn giữa các khu vực. Các chú cừu chỉ có thể di chuyển lên trên, xuống dưới, sang trái, sang phải khu vực bên cạnh, và không thể vượt qua được hàng rào.

Hai chú cừu A và B được gọi là ‘xa cách’ nếu như chúng không thể di chuyển tới vị trí của nhau. Các bạn hãy xác định xem số cặp chú cừu xa cách bằng nhau nhiêu?

**Input:** Dòng đầu tiên gồm 3 số nguyên dương N, K và M (1 ≤ N ≤ 100, K ≤ 100, M ≤ N^2). M dòng tiếp theo, mỗi dòng gồm 4 số nguyên u, v, x, y cho biết có rào chắn ở giữa hai khu vực (u, v) và (x, y) (2 ô này cạnh nhau). K dòng cuối, mỗi dòng chứa 2 số nguyên là tọa độ của mỗi chú cừu.

**Output**: In ra số cặp chú cừu bị xa cách tìm được.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 3 3 3  2 2 2 3  3 3 3 2  3 3 2 3  3 3  2 2  2 3 | 2 |

*Giải thích test: Cặp (3, 1) và (2, 1).*

### 1211 - MẠNG XÃ HỘI

Tý đang xây dựng một mạng xã hội và mời các bạn của mình dùng thử. Bạn của bạn cũng là bạn. Vì vậy, Tý muốn mạng xã hội của mình là hoàn hảo, tức với mọi bộ ba X, Y, Z, nếu X kết bạn với Y, Y kết bạn với Z thì X và Z cũng phải là bạn bè của nhau trên mạng xã hội.

Các bạn hãy xác định xem mạng xã hội hiện tại của Tý có là hoàn hảo hay không? Nếu có hãy in ra “YES”, “NO” trong trường hợp ngược lại.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi 2 số nguyên N và M (N, M ≤ 100 000).
- M dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v (u #v) cho biết u và v là kết bạn với nhau trên mạng xã hội của Tý.

**Output:**

- Với mỗi test, in ra đáp án tìm được trên một dòng.

**Ví dụ:**

| **Input:** | **Output** |
|---|---|
| 3  4 3  1 3  3 4  1 4  4 4  3 1  2 3  3 4  1 2  10 4  4 3  5 10  8 9  1 2 | YES  NO  YES |

### 1534 - KHÁM PHÁ HÀNH TRÌNH

Tốt nghiệp PTIT đúng hạn, Quân quyết định đi khám phá tất cả các thành phố ở đất nước mình. Có N thành phố và M tuyến đường bộ kết nối chúng với nhau. Quân cho rằng một hành trình thật “đẹp” là hành trình đi qua M-2 tuyến đường đúng hai lần, và đi qua 2 tuyến đường còn lại duy nhất một lần.

Quân có thể chọn thành phố xuất phát và kết thúc hành trình là tùy ý. Các bạn hãy tính giúp Quân xem có bao nhiêu cách để lựa chọn một hành trình đẹp? 2 hành trình A và B được coi là khác nhau, nếu như 2 tuyến đường đi qua duy nhất một lần của A và B là khác nhau.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 20).

Mỗi test bắt đầu bởi 2 số nguyên N và M (N, M &lt;= 100 000).

M dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v cho biết có cạnh nối giữa u và v. Dữ liệu đảm bảo các cạnh không trùng nhau. Có thể có cạnh nối u với chính nó, với mỗi đỉnh u có không quá 1 cạnh như vậy.

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

| Input: | Output |
|---|---|
| 3  5 4  1 2  1 3  1 4  1 5  5 3  1 2  2 3  4 5  2 2  1 1  1 2 | 6  0  1 |

Giải thích test 1: Các hành trình thỏa mãn:

2 → 1 → 3 → 1 → 4 → 1 → 5, 2 → 1 → 3 → 1 → 5 → 1 → 4,

2 → 1 → 4 → 1 → 5 → 1 → 3, 3 → 1 → 2 → 1 → 4 → 1 → 5,

3 → 1 → 2 → 1 → 5 → 1 → 4, 4 → 1 → 2 → 1 → 3 → 1 → 5.

### 1535 - ĐẾM SỐ MIỀN CỦA MA TRẬN

Cho ma trận A\[N\]\[M\] bao gồm các số 0 và 1. Ta gọi mỗi miền của ma trận A\[\]\[\] là nhóm các số 1 được bao quanh bởi các số 0. Hãy tìm số miền của ma trận. Ví dụ số miền của ma trận A\[\]\[\] là 4.

![](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)

Input:

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào N, M là cấp của ma trận A\[\]\[\]; dòng tiếp theo đưa vào N×M số A\[i\]\[j\] ; các số được viết cách nhau một vài khoảng trống.
- T, M, N, A\[i\]\[j\] thỏa mãn ràng buộc: 1≤ T ≤100; 1≤ M, N ≤100; 0≤ A\[i\]\[j\] ≤1.

Output:

- Đưa ra kết quả mỗi test theo từng dòng.

| Input: | Output: |
|---|---|
| 2    3 3    1 1 0 0 0 1 1 0 1    4 4    1 1 0 0 0 0 1 0 0 0 0 1 0 1 0 0 | 2  2 |

### 1536 - THAY THẾ O-X

Cho ma trận A\[N\]\[M\] có các phần tử hoặc là ký tự ‘’O’’ hoặc là ký tự ‘’X’’. Hãy thay thế các miền bao quanh ‘O’ bằng ‘X’. Một miền các ký tự ‘O’ bị bao quang bởi ký tự ‘X’ nếu các ký tự ‘X’ xuất hiện ở phía dưới, phía trên, bên trái, bên phải các ký tự ‘O’. Ví dụ với ma trận dưới đây ta sẽ có kết quả như sau:

X X X X X X X X

X O X X X X X X

![](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image001.png)X O O X X X X X

X O X X X X X X

X X O O X X O O

Input:

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm hai dòng: Dòng đầu tiên đưa vào hai số N, M ; dòng tiếp là N×M các phần tử của ma trận A\[\]\[\]; các phần tử được viết cách nhau một vài khoảng trống.
- T, N, M thỏa mãn ràng buộc: 1≤T≤100; 1≤ N, M ≤20.

Output:

- Đưa ra kết quả mỗi test theo từng dòng.

| Input: | Output: |
|---|---|
| 2    1 5    X O X O X     3 3    X X X  X O X  X X X | X O X O X    X X X  X X X  X X X |

### S305 - QUAY LẠI ĐỈNH 1

Cho đồ thị **có hướng** với N đỉnh và M cạnh. Người ta muốn thực hiện hành trình với hai bước di chuyển sau:

\- Bước 1: tìm đường đi từ đỉnh 1 qua các cạnh đến đỉnh 2.

\- Bước 2: từ đỉnh 2 lại đi qua các cạnh nào đó để quay lại đỉnh 1.

Không có cạnh nào được đi qua 2 lần. Hãy tính xem số đỉnh ít nhất cần phải đi qua trong hành trình đó là bao nhiêu.

**Input**

Dòng đầu ghi số bộ test.

Mỗi test bắt đầu với một dòng ghi hai số N, M (1 &lt; N&lt;=20).

Tiếp theo là M dòng ghi các cạnh có hướng. Không có cạnh nào trùng nhau.

**Output**

Với mỗi bộ test, ghi ra số đỉnh tối thiểu cần phải đi qua thỏa mãn yêu cầu đề bài.

**Ví dụ**

 | **Input** | **Ouput** |
|---|---|
| 2  6 7  1 3  3 4  4 5  5 1  4 2  2 6  6 3  9 11  1 3  3 4  4 2  2 5  5 3  3 6  6 1  2 7  7 8  8 9  9 1 | 6  6 |

### S306 - KHÔNG LIÊN THÔNG VỚI ĐỈNH 1

Cho đồ thị vô hướng G có N đỉnh, M cạnh.

Hãy liệt kê các đỉnh không cùng thành phần liên thông với đỉnh 1.

**Input**

Dòng đầu ghi 2 số N và M (0 &lt; N &lt; 300; 1 &lt;= M &lt;= N\*(N-1)/2)).

Tiếp theo là M dòng, mỗi dòng ghi một cạnh của đồ thị. Các cạnh được liệt kê với thứ tự bất kỳ.

**Output**

Ghi ra các đỉnh không liên thông với đỉnh 1 theo thứ tự tăng dần, mỗi dòng ghi một đỉnh. Nếu không có đỉnh nào thì ghi ra số 0.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 6 4  1 3  2 3  1 2  4 5 | 4  5  6 |

## ĐỒ THỊ CÓ TRỌNG SỐ

### 1214 - KRUSKAL

Cho đồ thị vô hướng có trọng số G=. Nhiệm vụ của bạn là hãy xây dựng một cây khung nhỏ nhất của đồ thị bằng thuật toán Kruskal.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào hai số V, E tương ứng với số đỉnh và số cạnh của đồ thị; phần thứ 2 đưa vào E cạnh của đồ thị, mỗi cạnh là một bộ 3: đỉnh đầu, đỉnh cuối và trọng số của cạnh.
- T, S, D thỏa mãn ràng buộc: 1≤T≤100; 1≤V≤100; 1≤E, W≤1000.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    3 3    1 2 5  2 3 3  1 3 1    2 1    1 2 5 | 4    5 |

### 1215 - PRIM

Cho đồ thị vô hướng có trọng số G=. Nhiệm vụ của bạn là hãy xây dựng một cây khung nhỏ nhất của đồ thị bằng thuật toán PRIM.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào hai số V, E tương ứng với số đỉnh và số cạnh của đồ thị; phần thứ 2 đưa vào E cạnh của đồ thị, mỗi cạnh là một bộ 3: đỉnh đầu, đỉnh cuối và trọng số của cạnh.
- T, S, D thỏa mãn ràng buộc: 1≤T≤100; 1≤V≤100; 1≤E, W≤1000.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

 **Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    3 3    1 2 5  2 3 3  1 3 1    2 1    1 2 5 | 4    5 |

### 1216 - CHU TRÌNH ÂM

Cho đồ thị có trọng số G= được biểu diễn dưới dạng danh sách cạnh trọng số âm hoặc dương. Hãy viết chương trình xác định xem đồ thị có chu trình âm hay không.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm |E|+1 dòng: dòng đầu tiên đưa vào hai số |V|, |E| tương ứng với số đỉnh và số cạnh của đồ thị; |E| dòng tiếp theo mỗi dòng đưa vào bộ ba uÎV, vÎV, w tương ứng với một cạnh cùng với trọng số canh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra 1 hoặc 0 theo từng dòng của mỗi test tương ứng với đồ thị có hoặc không có chu trình âm.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 2  3 3  1 2 -1  2 3 4  3 1 -2  3 3  1 2 -1  2 3 2  3 1 -2 | 0  1 |

### 1217 - DIJKSTRA.

Cho đồ thị có trọng số không âm G= được biểu diễn dưới dạng danh sách cạnh trọng số. Hãy viết chương trình tìm đường đi ngắn nhất từ đỉnh uÎV đến tất cả các đỉnh còn lại trên đồ thị.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm |E|+1 dòng: dòng đầu tiên đưa vào hai ba số |V|, |E| tương ứng với số đỉnh và uÎV là đỉnh bắt đầu; |E| dòng tiếp theo mỗi dòng đưa vào bộ ba uÎV, vÎV, w tương ứng với một cạnh cùng với trọng số canh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra kết quả của mỗi test theo từng dòng. Kết quả mỗi test là trọng số đường đi ngắn nhất từ đỉnh u đến các đỉnh còn lại của đồ thị theo thứ tự tăng dần các đỉnh.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 1  9 12 1  1 2 4  1 8 8  2 3 8  2 8 11  3 4 7  3 6 4  3 9 2  4 5 9  4 6 14  5 6 10  6 7 2  6 9 6 | 0 4 12 19 21 11 9 8 14 |

### 1218 - BELLMAN-FORD.

Cho đồ thị có hướng, có trọng số có thể âm hoặc không âm G= được biểu diễn dưới dạng danh sách cạnh. Hãy viết chương trình tìm đường đi ngắn nhất từ đỉnh uÎV đến tất cả các đỉnh còn lại trên đồ thị.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm |E|+1 dòng: dòng đầu tiên đưa vào hai ba số |V|, |E| tương ứng với số đỉnh và uÎV là đỉnh bắt đầu; |E| dòng tiếp theo mỗi dòng đưa vào bộ ba uÎV, vÎV, w tương ứng với một cạnh cùng với trọng số canh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;

**Output:**

- Đưa ra kết quả của mỗi test theo từng dòng. Kết quả mỗi test là trọng số đường đi ngắn nhất từ đỉnh u đến các đỉnh còn lại của đồ thị theo thứ tự tăng dần các đỉnh. Nếu tồn tại chu trình âm, in ra -1. Nếu không có đường đi ngắn nhất tới đỉnh u, in ra INFI.

 **Ví dụ:**

| **Input:** | **Output:** |
|---|---|
| 2  5 8 1  1 2 -1  1 3 4  2 3 3  2 4 2  2 5 2  4 2 1  4 3 5  5 4 -3  3 3 1  1 2 -1  2 3 2  3 1 -2 | 0 -1 2 -2 1  -1 |

### 1219 - NỐI ĐIỂM

Cho N điểm trên mặt phẳng Oxy. Để vẽ được đoạn thẳng nối A và B sẽ tốn chi phí tương đương với khoảng cách từ A tới B.

Nhiệm vụ của bạn là nối các điểm với nhau, sao cho N điểm đã cho tạo thành 1 thành phần liên thông duy nhất và chi phí để thực hiện là nhỏ nhất có thể.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi số nguyên N (1 ≤ N ≤ 100).
- N dòng tiếp theo, mỗi dòng gồm 2 số thực x\[i\], y\[i\] là tọa độ của điểm thứ i (|x\[i\]|, |y\[i\]| ≤ 100).

**Output:**

- Với mỗi test, in ra chi phí nhỏ nhất tìm được với độ chính xác 6 chữ số thập phân sau dấu phẩy.

**Ví dụ:**

| **Input:** | **Output** |
|---|---|
| 1  3  1.0 1.0  2.0 2.0  2.0 4.0 | 3.414214 |

### 1220 - ĐƯỜNG ĐI NGẮN NHẤT

Cho đơn đồ thị vô hướng liên thông G = (V, E) gồm N đỉnh và M cạnh, các đỉnh được đánh số từ 1 tới N và các cạnh được đánh số từ 1 tới M.

Có Q truy vấn, mỗi truy vấn yêu cầu bạn tìm đường đi ngắn nhất giữa đỉnh X\[i\] tới Y\[i\].

**Input:**

- Dòng đầu tiên hai số nguyên N và M (1 ≤ N ≤ 100, 1 ≤ M ≤ N\*(N-1)/2).
- M dòng tiếp theo, mỗi dòng gồm 3 số nguyên u, v, c cho biết có cạnh nối giữa đỉnh u và v có độ dài bằng c (1 ≤ c ≤ 1000).
- Tiếp theo là số lượng truy vấn Q (1 ≤ Q ≤ 100 000).
- Q dòng tiếp theo, mỗi dòng gồm 2 số nguyên X\[i\], Y\[i\].

**Output:**

- Với mỗi truy vấn, in ra đáp án là độ dài đường đi ngắn nhất tìm được.

**Ví dụ:**

| **Input:** | **Output** |
|---|---|
| 5 6  1 2 6  1 3 7  2 4 8  3 4 9  3 5 1  4 5 2  3  1 5  2 5  4 3 | 8  10  3 |

### 1221 - ĐẾM ĐƯỜNG ĐI NGẮN NHẤT

Cho đồ thị vô hướng liên thông G = (V, E) gồm N đỉnh và M cạnh, các đỉnh được đánh số từ 1 tới N và các cạnh được đánh số từ 1 tới M.

Nhiệm vụ của bạn là hãy tìm đường đi ngắn nhất từ 1 tới N và đếm xem có bao nhiêu tuyến đường có độ dài ngắn nhất như vậy?

**Input:**

- Dòng đầu ghi số bộ test, không quá 10. Mỗi bộ test gồm: 
    - Dòng đầu tiên hai số nguyên N và M (1 ≤ N ≤ 105, 1 ≤ M ≤ max(N\*(N-1)/2, 106).
    - M dòng tiếp theo, mỗi dòng gồm 3 số nguyên u, v, c cho biết có cạnh nối giữa đỉnh u và v có độ dài bằng c (1 ≤ c ≤ 106).

**Output:**

Với mỗi test, in ra 2 số nguyên là độ dài đường đi ngắn nhất và số lượng đường đi ngắn nhất. Input đảm bảo số lượng đường đi ngắn nhất không vượt quá 1018.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 5 6  1 2 6  1 3 7  2 4 2  3 4 9  3 5 3  4 5 2 | 10 2 |

Có 2 tuyến đường ngắn nhất: 1à 3 à 5 và 1 à 2 à 4 à 5.

### 1222 - DI CHUYỂN TRÊN BẢNG SỐ

Cho một bảng số kích thước N x M. Chi phí khi đi qua ô (i,j) bằng A\[i\]\[j\]. Nhiệm vụ của bạn là hãy tìm một đường đi từ ô (1, 1) tới ô (N, M) sao cho chi phí là nhỏ nhất. Tại mỗi ô, bạn được phép đi sang trái, sang phải, đi lên trên và xuống dưới.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi hai số nguyên N và M (1 ≤ N, M ≤ 500).
- N dòng tiếp theo, mỗi dòng gồm M số nguyên A\[i\]\[j\] (0 ≤ A\[i\]\[j\] ≤ 9).

**Output:**

- Với mỗi test, in ra một số nguyên là chi phí nhỏ nhất cho đường đi tìm được.

**Ví dụ:**

| **Input:** | **Output** |
|---|---|
| 3  4  5  0 3 1 2 9  7 3 4 9 9  1 7 5 5 3  2 3 4 2 5  1  6  0 1 2 3 4 5  5 5  1 1 1 9 9  9 9 1 9 9  1 1 1 9 9  1 9 9 9 9  1 1 1 1 1 | 24  15  13 |

### 1223 - ĐƯỜNG ĐI TRUNG BÌNH

Cho một đồ thị có hướng gồm N đỉnh và M cạnh. Nhiệm vụ của bạn là hãy tính khoảng cách trung bình ngắn nhất giữa hai nút bất kì nếu như chúng liên thông với nhau. Input đảm bảo rằng trong một nhóm liên thông, nếu như u đi tới được v thì v cũng đi tới được v với mọi cặp u, v.

**Input:**Dòng đầu tiên là số lượng bộ test T (T ≤ 20). Mỗi test bắt đầu bởi hai số nguyên N và M (1 ≤ N ≤ 100, M ≤ N\*(N-1)/2). M dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v cho biết có cạnh nối đơn hướng từ u tới v.

**Output:** Với mỗi test, in ra đáp án tìm được với độ chính xác 2 chữ số sau dấu phảy.

**Ví dụ:**

| **Input:** | **Output** |
|---|---|
| 2  4 5  1 2  2 4  1 3  3 1  4 3  7 5  1 2  1 4  4 2  2 7  7 1 | 1.83  1.75 |

Giải thích test 1: Ta có

d(1, 2) = 1, d(1, 3) = 1, d(1, 4) = 2; d (2, 1) = 3, d(2, 3) = 2, d(2, 4) = 1;

d(3, 1) = 1, d(3, 2) = 2, d(3, 4) = 3; d(4, 1) = 2, d(4, 2) = 3, d(4, 3) = 1.

Trung bình bằng 22/12 = 1.83

### 1537 - TÌM ĐƯỜNG

Cho một bảng S\[\]\[\] kích thước N x M, bao gồm các ô trống, các vật cản. Ban đầu bạn ở vị trí S. Nhiệm vụ của bạn là hãy di chuyển tới vị trí T, sao cho số lần đổi hướng không quá hai lần.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 20).

Mỗi test bắt đầu bởi hai số nguyên N và M (1 &lt;= N, M &lt;= 500).

N dòng tiếp theo, mỗi dòng gồm M kí tự mô tả bảng S. Trong đó: ‘.’ là một ô trống, ‘\*’ là vật cản, ‘S’ là vị trí xuất phát và ‘T’ là vị trí đích. (Chỉ có một vị trí S và T duy nhất).

**Output:**

Với mỗi test, in ra “YES” nếu tìm được đường đi, ra in “NO” trong trường hợp ngược lại.

**Test ví dụ:**

| Input: | Output |
|---|---|
| 2  5 5  ..S..  \*\*\*\*.  T....  \*\*\*\*.  .....  5 5  S....  \*\*\*\*.  .....  .\*\*\*\*  ..T.. | YES  NO |

### 1538 - HỆ THỐNG GIAO THÔNG

Mạng lưới giao thông ở 1 nước bao gồm N thành phố (đánh số từ 1 đến N) và N-1 đường nối các thành phố với nhau. Có một đường đi duy nhất giữa mỗi cặp thành phố và mỗi con đường có một độ dài xác định.

Nhiệm vụ của bạn là với mỗi K cặp thành phố cho trước, tìm độ dài của con đường ngắn nhất và dài nhất trên đường đi giữa 2 thành phố này.

**Input:**

Dòng đầu tiên chứa số nguyên N (2 ≤ N ≤ 100 000). N-1 dòng tiếp theo chứa 3 số nguyên A, B, C cho biết có một con đường độ dài C giữa thành phố A và thành phố B (1 &lt;= C &lt;= 1000000).

Dòng tiếp theo chứa số nguyên K là số lượng truy vấn (1 ≤ K ≤ 100 000).

K dòng tiếp theo, mỗi dòng gồm 2 số nguyên U và V.

**Output:**

Với mỗi truy vấn, in ra hai số nguyên là độ dài đường đi ngắn nhất và dài nhất tìm được.

**Test ví dụ:**

| Test 1 | Test 2 |
|---|---|
| Input:  5  2 3 100  4 3 200  1 5 150  1 3 50  3  2 4  3 5  1 2  Output:  100 200  50 150  50 100 | Input:  7  3 6 4  1 7 1  1 3 2  1 2 6  2 5 4  2 4 4  5  6 4  7 6  1 2  1 3  3 5  Output:  2 6  1 4  6 6  2 2  2 6 |

### 1539 - HÀNH TRÌNH DU LỊCH

Một đất nước nọ có N thành phố, được đánh dấu từ 1 tới N. Giữa thành phố thứ i và i+1 có một tuyến đường trực tiếp với độ dài bằng W\[i\]. Đi quãng đường có độ dài bằng 1, chiếc xe của bạn tiêu tốn mất 1 lít xăng. Giả sử rằng bình xăng của bạn có thể chứa được nhiều xăng vô kể.

Khi đến thành phố i, bạn sẽ nhận được thêm một lượng xăng bằng G\[i\], như một món quà mà người dân địa phương ở đây dành cho bạn. Nếu bạn muốn thêm xăng, giá bán cho mỗi lít xăng là P\[i\] đồng / 1 lít.

Có Q truy vấn, mỗi truy vấn sẽ là một hành trình đi từ thành phố X\[i\] tới Y\[i\]. Bạn hãy tính lượng tiền ít nhất cần bỏ ra để có thể hoàn thành hành trình này?

Lưu ý: Khi vừa đến 1 thành phố, nếu bạn hết xăng thì vẫn được. Tuy nhiên, khi đang đi mà hết xăng thì không thể đi được nữa.

**Input:**

Dòng đầu tiên gồm 2 số nguyên N và Q (2 ≤ N, Q ≤ 200 000).

Dòng tiếp theo gồm N-1 số nguyên W\[i\] (1 &lt;= W\[i\] &lt;= 10^6).

N dòng tiếp, mỗi dòng gồm 2 số nguyên G\[i\] và P\[i\] (1 &lt;= G\[i\], P\[i\] &lt;= 10^6).

Q dòng tiếp theo, mỗi dòng gồm 2 số nguyên X\[i\], Y\[i\].

**Output:**

Với mỗi truy vấn, in ra một số nguyên là đáp án tìm được.

**Test ví dụ:**

| Input: | Output: |
|---|---|
| 6 4  2 6 1 5 3  3 1  4 2  3 1  1 4  4 6  9 3  2 5  1 6  3 5  4 6 | 6  3  2  16 |

Giải thích test 1: Đi từ thành phố 2 tới thành phố 5.

Tại thành phố 2, bạn được tặng 4 lít xăng, cần phải mua thêm 2 lít xăng nữa (mất 4 đồng) để có đủ 6 lít xăng đi tới thành phố 3.

Tại thành phố 3, bạn được thưởng 3 lít xăng. Giải pháp tối ưu là mua thêm 2 lít xăng tại đây (mất 2 đồng) để có được 5 lít xăng.

Tới thành phố 4, bạn có 4 lít xăng, được thưởng thêm 1 lít xăng nữa, vừa đủ để hoàn thành chuyến đi tới thành phố 5.

Tổng chi phí cho chuyến đi bằng 4 + 2 = 6.

### 1540 - LUỒNG CỰC ĐẠI TRÊN MẠNG

Cho mạng G = (E, V) có N đỉnh và M cạnh, đỉnh phát S và đỉnh thu T. Mỗi cạnh e = (u, v) có khả năng thông qua bằng c(e). Nhiệm vụ của bạn là hãy tìm khả năng thông qua lớn nhất từ đỉnh S tới đỉnh T.

 **Input:**

Dòng đầu tiên chứa số nguyên N và M (2 ≤ N &lt;= 100, 2 &lt;= M ≤ 1000).

M dòng tiếp theo, mỗi dòng gồm 3 số nguyên dương u, v, c cho biết cạnh từ u tới v có khả năng thông qua bằng c (1 &lt;= c &lt;= 100).

**Output:**

In ra một số nguyên là luồng cực đại trên mạng.

**Test ví dụ:**

| Test 1 | Test 2 |
|---|---|
| Input:  6 10 1 6  1 2 16  1 4 13  2 4 10  4 2 4  2 3 12  3 4 9  3 6 20  4 5 14  5 3 7  5 6 4  Output:  23 | Input:  4 5 1 4  1 2 10  1 3 5  2 3 15  2 4 5  3 4 10  Output:  15 |

### 1541 - CHUYẾN TÀU

Ngày khai trương tuyến đường sắt Cát Linh – Hà Đông, đã có rất nhiều người tới mua vé để trải nghiệm. Mỗi chuyến tàu gồm có N ghế, đánh số từ 1 tới N. Có M chiếc vé đã được bán ra. Một số người muốn được trải nghiệm nhiều lần, nên họ đã rất mua nhiều vé.

Do sơ xuất không ghi mốc thời gian trên vé, nên ban quản lý đã phải rất mệt nhọc trong việc sắp xếp ghế ngồi cho các vị khách. Chuyến tàu sẽ chạy tất cả X lượt, để phục vụ tất cả số lượng vé đã bán ra. Một người có 1 vé sẽ được lên một chuyến tàu, và phải đảm bảo rằng không có chuyện hai người phải ngồi chung một ghế.

Nhận thấy rằng có nhiều vị trí ghế còn trống, trong khi có hành khách không được lên chuyến tàu vì vị trí ghế mà họ đặt trùng với cả người khác, ban quản lý đã thuyết phục những người này đổi vé, lấy một vé khác mà vị trí ghế còn trống. Các vị khách rất khó tính, họ chỉ đồng ý đổi vé nếu như vị trí ghế ngồi của vé mới nhỏ hơn chiếc vé hiện tại mà họ đang có.

Ban quản lý muốn sắp xếp một cách tối ưu, sao cho số lượt chuyến tàu chạy là ít nhất. Bạn hãy xác định xem số lượt tàu chạy ít nhất bằng bao nhiêu? Và trong trường hợp sắp xếp tối ưu như vậy, số lượng đổi vé ít nhất bằng bao nhiêu?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 100).

Mỗi test bắt đầu bằng ba số nguyên N, M và C. N là số ghế, M là số vé bán ra, và C là chỉ số hành khách lớn nhất. (1 &lt;= N &lt;= 1000, 2 &lt;= M, C &lt;= 1000).

M dòng tiếp theo, mỗi dòng gồm 2 P\[i\] và B\[i\] (1 &lt;= P\[i\] &lt;= N, 1 &lt;= B\[i\] &lt;= C) cho biết hành khách B\[i\] đã mua vé có vị trí ghế ngồi là P\[i\].

**Output:**

Với mỗi test, in ra 2 số nguyên X, Y, trong đó X là số lượt tàu chạy nhỏ nhất và Y là số lượng đổi vé ít nhất.

**Test ví dụ:**

| Input: | Output |
|---|---|
| 5  2 2 2  2 1  2 2  2 2 2  1 1  1 2  2 2 2  1 1  2 1  1000 1000 4  3 2  2 1  3 3  3 1  3 3 5  3 1  2 2  3 3  2 2  3 1 | 1 1  2 0  2 0  2 1  2 1 |

Giải thích test 1: Cả 2 vị khách cùng mua vé có vị trí ghế ngồi là 2, vì vậy cần bảo một người đổi vé lấy vị trí 1. Chỉ cần 1 chuyến tàu là 2 người có thể đi được.

Giải thích test 2: Cả 2 vị khách cùng mua vé có ghế ngồi là 1, nên không thể bảo ai đổi vé được nữa. Do đó, cần 2 chuyến tàu.

Giải thích test 3: Có 1 vị khách và người này mua 2 vé. Do đó, cần có 2 chuyến tàu.

Giải thích test 4: Ghế 3 có ba người mua (1, 2, 3), ghế 2 có một người mua (1). Một cách tối ưu là bảo người số 2 đổi vé lấy ghế 2. Khi đó, ghế 2 có (1, 2), ghế 3 có (1, 3) và chỉ cần 2 chuyến tàu là đủ.

Giải thích test 5: Phương án tối ưu là người 1 có vị trí ghế 3 yêu cầu đổi xuống ghế 1 (đổi 1 lần).

### 1542 - ĐƯỜNG ĐI TRUNG BÌNH NGẮN NHẤT

Tại đất nước Highland có N thành phố, mỗi cặp thành phố được kết nối với nhau bởi một tuyến đường một chiều duy nhất. Chi phí di chuyển giữa thành phố thứ u tới thành phố v là C\[u\]\[v\].

Bạn cần tìm một hành trình thỏa mãn các yêu cầu:

- Có thể xuất phát ở bất cứ đâu, nhưng kết thúc hành trình phải quay lại điểm xuất phát.
- Phải đi qua ít nhất 2 tuyến đường.
- Chi phí trung bình trên mỗi tuyến đường là nhỏ nhất (Lấy tổng chi phí / số tuyến đường đi qua).

**Input:**

Dòng đầu tiên là số lượng thành phố N (2 &lt;= N &lt;= 500).

N dòng tiếp theo, mỗi dòng gồm N số nguyên cho biết chi phí di chuyển từ thành phố u tới v. C\[u\]\[u\] = 0 và 1 &lt;= C\[u\]\[v\] &lt;= 200.

**Output:**

In ra chi phí trung bình trên mỗi tuyến đường nhỏ nhất tìm được, dưới dạng phân số A/B, trong đó ước chung lớn nhất của A và B bằng 1.

**Test ví dụ:**

| Test 1 | Test 2 |
|---|---|
| Input:  2  0 1  2 0  Output:  3/2 | Input:  3  0 2 6  4 0 2  1 9 0  Output:  5/3 |

### 1543 - XÂY DỰNG THÀNH PHỐ

Đất nước Middleland đang phải kiến thiết lại đất nước sau trận động đất kinh hoàng. Kế hoạch được chính phủ đề ra là phải hoàn thành tất cả các con đường kết nối N thành phố trong M ngày.

Đội ngũ kỹ sư đã lên kế hoạch như sau: ngày thứ i sẽ xây dựng các tuyến đường kết nối các cặp thành phố a và b thỏa mãn gcd(a, b) = M-i+1.

Cho Q truy vấn, mỗi truy vấn có dạng u, v, yêu cầu bạn xác định ngày mà 2 thành phố u và v có thể kết nối được với nhau.

**Input:**

Dòng đầu tiên gồm 3 số nguyên N, M, Q (1 &lt;= N, Q &lt;= 100 000, 1 &lt;= M &lt;= N).

Q dòng tiếp theo, mỗi dòng gồm 2 số nguyên mô tả một truy vấn.

**Output:**

Với mỗi truy vấn, in ra ngày mà hai thành phố được liên thông với nhau.

**Test ví dụ:**

| Test 1 | Test 2 |
|---|---|
| Input:  8 3 3  2 5  3 6  4 8  Output:  3    1    2 | Input:  25 6 1  20 9  Output:  4 |

Giải thích test 1:

Ngày đầu tiên, con đường giữa hai thành phố (3, 6) được xây dựng.

Ngày thứ hai, con đường giữa (2, 4), (2, 6), (2, 8), (4, 6) và (6, 8) được hoàn thiện. Do đó có thể di chuyển giữa thành phố 4 và 8 (qua trung gian là 6).

Ngày cuối cùng, tất cả các con đường lại lại được hoàn thành.

### 1544 - ĐIỂM HẸN

Sau nhiều ngày ở nước ngoài, ngày trở về quê hương Tí rất muốn gặp mặt các bạn cũ của mình. Tại quê nhà, Tí có N người bạn, mỗi bạn lại sống ở một thị trấn khác nhau trong thành phố. Có M tuyến đường kết nối các thị trấn này với nhau. Tí muốn chọn một địa điểm gặp mặt tối ưu (điểm P) trên tuyến đường thứ K, sao cho giá trị lớn nhất độ dài quãng đường cần phải di chuyển của N bạn tới điểm P là nhỏ nhất.

Các bạn hãy giúp Tí tìm điểm P tối ưu nhất.

**Input**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 10).

Mỗi test bắt đầu bởi 3 số nguyên N, M và K (2 &lt;= N, M &lt;= 100 000).

M dòng tiếp theo, mỗi dòng gồm 3 số nguyên u, v, c (c &lt;= 10^9) cho biết có một tuyến đường 2 chiều kết nối thành phố u và v.

Input đảm bảo đơn đồ thị và không có tuyến đường nào tự kết nối thị trấn nào đó.

**Output**

Với mỗi test, in ra hai số thực X và Y với 5 chữ số sau dấu phảy, với X là khoảng cách giữa P và A, còn Y là giá trị lớn nhất của các đường đi ngắn nhất từ P tới các thị trấn 1, 2, …, N.

Thứ tự u, v của mỗi tuyến đường được giữ nguyên. Giả sử điểm P cần tìm kết nối thị trấn A và B. Khoảng cách giữa P và A bằng 8, P và B bằng 2, bạn phải in ra 8.

Nếu có nhiều đáp án, hãy tìm điểm P gần A nhất.

**Test ví dụ:**

| Input | Output |
|---|---|
| 2  2 1 1  1 2 10  4 4 1  1 2 10  2 3 10  3 4 1  4 1 5 | 5.00000 5.00000  2.00000 8.00000 |

Giải thích test 2: Điểm hẹn P nằm giữa thị trấn của hai bạn 1 và 2, cách thị trấn 1 khoảng cách bằng 2.

Khoảng cách bạn 1 phải di chuyển là 2.

Khoảng cách bạn 2 phải di chuyển là 8.

Khoảng cách bạn 3 phải di chuyển là 8.

Khoảng cách bạn 4 phải di chuyển là 7.

## ÔN TẬP CÁC THUẬT TOÁN CƠ BẢN

### 1309 - XÂU NHỊ PHÂN KẾ TIẾP

Cho xâu nhị phân X\[\], nhiệm vụ của bạn là hãy đưa ra xâu nhị phân tiếp theo của X\[\]. Ví dụ X\[\] =”010101” thì xâu nhị phân tiếp theo của X\[\] là “010110”.

Input:

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu nhi phân X.
- T, X\[\] thỏa mãn ràng buộc: 1≤T≤100; 1≤length(X)≤103.
 
Output:

- Đưa ra kết quả mỗi test theo từng dòng.
 
 | **Input** | **Output** |
|---|---|
| 2  010101  111111 | 010110  000000 |

### 1310 - TẬP CON KẾ TIẾP

Cho hai số N, K và một tập con K phần tử X\[\] =(X1, X2,.., XK) của 1, 2, .., N. Nhiệm vụ của bạn là hãy đưa ra tập con K phần tử tiếp theo của X\[\]. Ví dụ N=5, K=3, X\[\] ={2, 3, 4} thì tập con tiếp theo của X\[\] là {2, 3, 5}.

Input:

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là hai số N và K; dòng tiếp theo đưa vào K phần tử của X\[\] là một tập con K phần tử của 1, 2, .., N.
- T, K, N, X\[\] thỏa mãn ràng buộc: 1≤T≤100; 1≤K≤N≤103.
 
Output:

- Đưa ra kết quả mỗi test theo từng dòng.
 
 | Input | Output |
|---|---|
| 2  5 3  1 4 5  5 3  3 4 5 | 2 3 4  1 2 3 |

### 1311 - HOÁN VỊ KẾ TIẾP

Cho số tự nhiên N và một hoán vị X\[\] của 1, 2, .., N. Nhiệm vụ của bạn là đưa ra hoán vị tiếp theo của X\[\]. Ví dụ N=5, X\[\] = {1, 2, 3, 4, 5} thì hoán vị tiếp theo của X\[\] là {1, 2, 3, 5, 4}.

Input:

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là số N; dòng tiếp theo đưa vào hoán vị X\[\] của 1, 2, .., N.
- T, N, X\[\] thỏa mãn ràng buộc: 1≤T≤100; 1≤ N≤103.
 
Output:

- Đưa ra kết quả mỗi test theo từng dòng.
 
 | Input | Output |
|---|---|
| 2  5  1 2 3 4 5  5  5 4 3 2 1 | 1 2 3 5 4  1 2 3 4 5 |

### 1312 - XÂU NHỊ PHÂN TRƯỚC

Cho xâu nhị phân X\[\], nhiệm vụ của bạn là hãy đưa ra xâu nhị phân trước của X\[\]. Ví dụ X\[\] =”111111” thì xâu nhị phân trước của X\[\] là “111110”. Với xâu X\[\] =“000001” thì xâu nhị trước của X\[\] là “000000”. Chú ý: nếu xâu dữ liệu trong input là xâu đầu tiên thì trước nó sẽ là xâu cuối cùng.

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu nhi phân X.
- T, X\[\] thỏa mãn ràng buộc: 1≤T≤100; 1≤length(X)≤103.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  010101  111111 | 010100  111110 |

### 1313 - TẬP CON LIỀN KỀ PHÍA TRƯỚC

Cho hai số N, K và một tập con K phần tử X\[\] =(X1, X2,.., XK) của 1, 2, .., N. Nhiệm vụ của bạn là hãy đưa ra tập con K phần tử trước đó của X\[\]. Ví dụ N=5, K=3, X\[\] ={2, 3, 5} thì tập con trước đó của X\[\] là {2, 3, 4}. Chú ý nếu tập con trong input là đầu tiên thì trước đó là tập con cuối cùng.

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là hai số N và K; dòng tiếp theo đưa vào K phần tử của X\[\] là một tập con K phần tử của 1, 2, .., N.
- T, K, N, X\[\] thỏa mãn ràng buộc: 1≤T≤100; 1≤K≤N≤103.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5 3  2 3 5  5 3  1 2 3 | 2 3 4  3 4 5 |

### 1314 - PHÂN TÍCH SỐ

Cho số nguyên dương N. Nhiệm vụ của bạn là hãy liệt kê tất cả các cách phân tích số tự nhiên N thành tổng các số tự nhiên nhỏ hơn hoặc bằng N. Phép hoán vị của một cách được xem là giống nhau. Ví dụ với N = 5 ta có kết quả là: (5), (4, 1), (3, 2), (3, 1, 1), (2, 2, 1), (2, 1, 1, 1), (1, 1, 1, 1, 1) .

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một số tự nhiên N được viết trên một dòng.
- T, n thỏa mãn ràng buộc: 1≤T, N≤10.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  4  5 | (4) (3 1) (2 2) (2 1 1) (1 1 1 1)  (5) (4 1) (3 2) (3 1 1) (2 2 1) (2 1 1 1) (1 1 1 1 1) |

### 1315 - HOÁN VỊ NGƯỢC

Cho số nguyên dương N. Nhiệm vụ của bạn là hãy liệt kê tất cả các hoán vị của 1, 2, .., N theo thứ tự ngược. Ví dụ với N = 3 ta có kết quả: 321, 312, 231, 213, 132, 123.

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một số tự nhiên N được viết trên một dòng.
- T, n thỏa mãn ràng buộc: 1≤T, N≤10.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  2  3 | 21 12  321 312 231 213 132 123 |

### 1316 - LIỆT KÊ TẬP CON

Cho một xâu ký tự S không có ký tự lặp lại. Hãy đưa ra tất cả các tập con của xâu ký tự S theo thứ tự tăng dần của các xâu ký tự.

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu ký tự.
- T, S thỏa mãn ràng buộc: 1≤T≤100; 1≤length(S)≤16.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1    3    abc | a ab abc ac b bc c |

### 1317 - DI CHUYỂN TRONG MÊ CUNG 1

Cho một mê cung bao gồm các khối được biểu diễn như một ma trận nhị phân A\[N\]\[N\]. Một con chuột đi từ ô đầu tiên góc trái (A\[0\]\[0\]) đến ô cuối cùng góc phải (A\[N-1\]\[N-1\]) theo nguyên tắc:

- Down (D): Chuột được phép xuống dưới nếu ô dưới nó có giá trị 1.
- Right (R): Chuột được phép sang phải dưới nếu ô bên phải nó có giá trị 1.
 
Hãy đưa ra một hành trình của con chuột trên mê cung. Đưa ra -1 nếu chuột không thể đi đến đích.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào số N là kích cỡ của mê cung; dòng tiếp theo đưa vào ma trận nhị phân A\[N\]\[N\].
- T, N, A\[i\]\[j\] thỏa mãn ràng buộc: 1≤T ≤10; 2≤N≤10; 0≤A\[i\]\[j\] ≤1.
 
**Output:**

- Đưa ra tất cả đường đi của con chuột trong mê cung theo thứ tự từ điển. Đưa ra -1 nếu chuột không đi được đến đích.
 
 | Input | Output |
|---|---|
| 2  4  1 0 0 0  1 1 0 1  0 1 0 0  1 1 1 1  5  1 0 0 0 0  1 1 1 1 1  1 1 0 0 1  0 1 1 1 1  0 0 0 1 1 | DRDDRR  DDRDRRDR DDRDRRRD DRDDRRDR DRDDRRRD DRRRRDDD |

### 1318 - DI CHUYỂN TRONG MÊ CUNG 2

Cho một mê cung bao gồm các khối được biểu diễn như một ma trận nhị phân A\[N\]\[N\]. Một con chuột đi từ ô đầu tiên góc trái (A\[0\]\[0\]) đến ô cuối cùng góc phải (A\[N-1\]\[N-1\]) theo nguyên tắc:

- Down (D): Chuột được phép xuống dưới nếu ô dưới nó có giá trị 1.
- Right (R): Chuột được phép sang phải dưới nếu ô bên phải nó có giá trị 1.
- Left (L): Chuột được phép sang trái dưới nếu ô bên trái nó có giá trị 1.
- Up (U): Chuột được phép lên trên nếu ô trên nó có giá trị 1.
 
Hãy đưa ra tất cả các hành trình của con chuột trên mê cung. Đưa ra -1 nếu chuột không thể đi đến đích.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào số N là kích cỡ của mê cung; dòng tiếp theo đưa vào ma trận nhị phân A\[N\]\[N\].
- T, N, A\[i\]\[j\] thỏa mãn ràng buộc: 1≤T ≤10; 2≤N≤8; 0≤A\[i\]\[j\] ≤1.
 
**Output:**

- Đưa ra các xâu ký tự được sắp xếp, trong đó mỗi xâu là một đường đi của con chuột trong mê cung. In ra đáp án theo thứ tự từ điển. Đưa ra -1 nếu chuột không đi được đến đích.
 
 | Input | Output |
|---|---|
| 3    4    1 0 0 0  1 1 0 1  0 1 0 0  0 1 1 1    4    1 0 0 0  1 1 0 1  1 1 0 0  0 1 1 1  5  1 0 0 0 0  1 1 1 1 1  1 1 1 0 1  0 0 0 0 1  0 0 0 0 1 | DRDDRR  DDRDRR DRDDRR  DDRRURRDDD DDRURRRDDD DRDRURRDDD DRRRRDDD |

### 1319 - ĐỔI CHỖ CÁC CHỮ SỐ

Cho số tự nhiên K và xâu ký tự các chữ số S. Nhiệm vụ của bạn là đưa ra số lớn nhất bằng cách thực hiện nhiều nhất K lần đổi chỗ các ký tự trong S. Ví dụ K =3 và S = “1234567” ta được “7654321”.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là số K; dòng tiếp theo là xâu ký tự S.
- T, K, S thỏa mãn ràng buộc: 1≤T ≤100; 1≤K≤10; 1≤.lenght(S)≤7.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 | Input | Output |
|---|---|
| 3    4    1234567    3    3435335    2    1034 | 7654321    5543333    4301 |

### 1320 - TỔ HỢP SỐ CÓ TỔNG BẰNG X

Cho mảng A\[\] gồm N số nguyên dương phân biệt và số X. Nhiệm vụ của bạn là tìm phép tổ hợp các số trong mảng A\[\] có tổng bằng X. Các số trong mảng A\[\] có thể được sử dụng nhiều lần. Mỗi tổ hợp các số của mảng A\[\] được in ra theo thứ tự không giảm các số. Ví dụ với A\[\] = {2, 4, 6, 8}, X = 8 ta có các tổ hợp các số như sau:

\[2, 2, 2, 2\], \[2, 2, 4\], \[2, 6\], \[4, 4\], \[8\].

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất là hai số N và X; dòng tiếp theo đưa vào N số của mmảng A\[\]; các số được viết cách nhau một vài khoảng trống.
- T, N, X, A\[i\] thỏa mãn ràng buộc: 1≤T ≤10; 1≤X, A\[i\]≤100. N ≤ 20.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng. Mỗi đường tổ hợp được bao bởi cặp ký tự \[, \]. Đưa ra -1 nếu không có tổ hợp nào thỏa mãn yêu cầu bài toán.
 
 | Input | Output |
|---|---|
| 1    4 8  2 4 6 8 | \[2 2 2 2\] \[2 2 4\] \[2 6\] \[4 4\] \[8\] |

### 1321 - SẮP XẾP CÔNG VIỆC

Cho hệ gồm N hành động. Mỗi hành động được biểu diễn như một bộ đôi &lt;Si, Fi&gt; tương ứng với thời gian bắt đầu và thời gian kết thúc của mỗi hành động. Hãy tìm phương án thực hiện nhiều nhất các hành động được thực hiện bởi một máy hoặc một người sao cho hệ không xảy ra mâu thuẫn.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm 3 dòng: dòng thứ nhất đưa vào số lượng hành động N; dòng tiếp theo đưa vào N số Si tương ứng với thời gian bắt đầu mỗi hành động; dòng cuối cùng đưa vào N số Fi tương ứng với thời gian kết thúc mỗi hành động; các số được viết cách nhau một vài khoảng trống.
- T, N, Si, Fi thỏa mãn ràng buộc: 1≤T≤100; 1≤N, Fi, Si≤1000.
 
**Output:**

- Đưa số lượng lớn nhất các hành động có thể được thực thi bởi một máy hoặc một người.
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 1  6  1 3 0 5 8 5  2 4 6 7 9 9 | 4 |

### 1322 - NỐI DÂY

Cho N sợi dây với độ dài khác nhau được lưu trong mảng A\[\]. Nhiệm vụ của bạn là nối N sợi dây thành một sợi sao cho tổng chi phí nối dây là nhỏ nhất. Biết chi phí nối sợi dây thứ i và sợi dây thứ j là tổng độ dài hai sợi dây A\[i\] và A\[j\].

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất đưa vào số lượng sợi dây N; dòng tiếp theo đưa vào N số A\[i\] là độ dài của các sợi dây; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤106; 0≤A\[i\]≤106.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2    4    4 3 2 6    5    4 2 7 6 9 | 29    62 |

### 1323 - SỐ KHỐI LẬP PHƯƠNG

Một số X được gọi là số khối lập phương nếu X là lũy thừa bậc 3 của số Y (X= Y3). Cho số nguyên dương N, nhiệm vụ của bạn là tìm số khối lập phương lớn nhất bằng cách loại bỏ đi các chữ số của N. Ví dụ số 4125 ta có kết quả là 125 = 53.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một số tự nhiên N được viết trên một dòng.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤1018.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng. Nếu không tìm được đáp án in ra -1.
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2    4125    976 | 125    -1 |

### 1324 - PHÂN SỐ ĐƠN VỊ

Một phân số đơn vị nếu tử số của phân số đó là 1. Mọi phân số nguyên dương đều có thể biểu diễn thành tổng các phân số đơn vị. Ví dụ 2/3 = 1/2 + 1/6. Cho phân số nguyên dương P/Q bất kỳ (P &lt; Q), hãy biểu diễn phân số nguyên dương thành tổng phân số đơn vị.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là bộ đôi tử số P và mẫu số Q của phân số nguyên dương được viết trên một dòng.
- T, P, Q thỏa mãn ràng buộc: 1≤T≤100; 1≤P, Q≤100.
 
**Output:**

- Đưa ra đáp án tìm được trên 1 dòng, theo dạng “1/a + 1/b + …”
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2  2 3  1 3 | 1/2 + 1/6  1/3 |

### 1325 - GẤP ĐÔI DÃY SỐ

Một dãy số tự nhiên bắt đầu bởi con số 1 và được thực hiện N-1 phép biến đổi “gấp đôi” dãy số như sau:

Với dãy số A hiện tại, dãy số mới có dạng A, x, A trong đó x là số tự nhiên bé nhất chưa xuất hiện trong A.

Ví dụ với 2 bước biến đổi, ta có \[1\] à \[1 2 1\] à \[1 2 1 3 1 2 1\].

Các bạn hãy xác định số thứ K trong dãy số cuối cùng là bao nhiêu?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test gồm số nguyên dương N và K (1 ≤ N ≤ 50, 1 ≤ K ≤ 2N - 1).

**Output:**

Với mỗi test, in ra đáp án trên một dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  3 2  4 8 | 2  4 |

Giải thích test 1: Dãy số thu được là \[1, 2, 1, 3, 1, 2, 1\].

Giải thích test 2: Dãy số thu được là \[1, 2, 1, 3, 1, 2, 1, 4, 1, 2, 1, 3, 1, 2, 1\].

### 1326 - DÃY XÂU FIBONACI

Một dãy xâu ký tự G chỉ bao gồm các chữ cái A và B được gọi là dãy xâu Fibonacci nếu thỏa mãn tính chất: *G(1) = A; G(2) = B; G(n) = G(n-2)+G(n-1).* Với phép cộng (+) là phép nối hai xâu với nhau. Bài toán đặt ra là tìm ký tự ở vị trí thứ i (tính từ 1) của xâu Fibonacci thứ n.

**Dữ liệu vào:** Dòng 1 ghi số bộ test. Mỗi bộ test ghi trên một dòng 2 số nguyên N và i (1&lt;N&lt;93). Số i đảm bảo trong phạm vi của xâu G(N) và không quá 18 chữ số. **Kết quả:** Ghi ra màn hình kết quả tương ứng với từng bộ test.

 | **Input** | **Output** |
|---|---|
| 2  6 4  8 19 | A  B |

### 1327 - SỐ FIBONACCI THỨ N

Dãy số Fibonacci được xác định bằng công thức như sau:

F\[0\] = 0, F\[1\] = 1;

F\[n\] = F\[n-1\] + F\[n-2\] với mọi n &gt;= 2.

Các phần tử đầu tiên của dãy số là 0, 1, 1, 2, 3, 5, 8, ...

Nhiệm vụ của bạn là hãy xác định số Fibonaci thứ n. Do đáp số có thể rất lớn, in ra kết quả theo modulo 109+7.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 1000).

Mỗi test bắt gồm một số nguyên N (1 ≤ N ≤ 109).

**Output:**

Với mỗi test, in ra đáp án trên một dòng.

**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 3  2  6  20 | 1  8  6765 |

### 1328 - LŨY THỪA MA TRẬN

Cho ma trận vuông A kích thước N x N. Nhiệm vụ của bạn là hãy tính ma trận X = AK với K là số nguyên cho trước. Đáp số có thể rất lớn, hãy in ra kết quả theo modulo 109+7.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 100).

Mỗi test bắt gồm một số nguyên N và K (1 ≤ N ≤ 10, 1 ≤ K ≤ 109) là kích thước của ma trận và số mũ.

**Output:**

Với mỗi test, in ra kết quả của ma trận X.

**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  2 5  1 1  1 0  3 1000000000  1 2 3  4 5 6  7 8 9 | 8 5  5 3  597240088 35500972 473761863  781257150 154135232 527013321  965274212 272769492 580264779 |

### CP01002 - TỔNG GIAI THỪA

Cho số nguyên dương N

Viết chương trình tính tổng S = 1 + 1.2 + 1.2.3 + ...+1.2.3...n.

**Dữ liệu vào:**

Chỉ có một dòng ghi số n không quá 20.

**Kết quả:**

Được ghi trên một dòng duy nhất.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3 | 9 |

### CP01006 - DÃY CON LIÊN TIẾP

Cho dãy số A\[\] gồm có N phần tử. Nhiệm vụ của bạn là hãy một dãy con liên tiếp sao cho tổng các phần tử của chúng là lớn nhất.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm số nguyên N (1≤ N ≤ 100 000), số lượng phần tử trong dãy số ban đầu.

Dòng tiếp theo gồm N số nguyên A\[i\] (-10^9 ≤ A\[i\] ≤ 10^9).

**Output:**

Với mỗi test, in ra một số nguyên là đáp án của bài toán trên một dòng.

**Ví dụ:**

 | Input: | Output |
|---|---|
| 2  8  -2 -3 4 -1 -2 1 5 -3  5  1 2 3 4 5 | 7  15 |

**Giải thích test 1:**

4 + (-1) + (-2) + 1 + 5 = 7

### CP01007 - SỐ ĐỨNG ĐẦU

Cho dãy số A\[\] gồm có N phần tử. Một phần tử được gọi là số đứng đầu nếu như nó lớn hơn tất cả các phần tử nằm bên phải của nó.

Nhiệm vụ của bạn là hãy tìm các số đứng đầu trong dãy số A\[\] đã cho.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm số nguyên N (1≤ N ≤ 1000), số lượng phần tử trong dãy số ban đầu.

Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 10^6).

**Output:**

Với mỗi test, in ra trên một dòng các số tìm được, in ra theo thứ tự giảm dần.

**Ví dụ:**

 | Input: | Output |
|---|---|
| 1  6  16 17 4 3 5 2 | 17 5 2 |

### CP01008 - QUAY VÒNG DÃY SỐ

Cho dãy số A\[\] gồm có N phần tử. Nhiệm vụ của bạn là hãy chuyển D phần tử đầu tiên của dãy A\[\] xuống cuối dãy.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm số nguyên N và D (1≤ N ≤ 1000, 0 ≤ D ≤ N).

Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 10^6).

**Output:**

Với mỗi test, in ra trên một dòng là dãy số thu được sau khi thực hiện phép quay vòng.

**Ví dụ:**

 | Input: | Output |
|---|---|
| 1  7 2  1 2 3 4 5 6 7 | 3 4 5 6 7 1 2 |

### CP01015 - TÌM SỐ DƯ

Hãy tính giá trị biểu thức ![](data:image/png;base64,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).

**Input:**

Dòng đầu là số lượng bộ test T (T ≤ 100).

Mỗi test gồm một xâu biểu diễn số nguyên n, n có không quá 100 000 kí tự.

**Output:**

Với mỗi test in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 2  4  123456789 | 4  0 |

### CP01016 - ƯỚC SỐ CHUNG LỚN NHẤT (GCD)

Cho dãy số A\[\] nguyên dương có N phần tử. Bạn cần xây dựng dãy số B có N+1 phần tử sao cho gcd(B\[i\], B\[i+1\]) = A\[i\] với mọi i thỏa mãn 1 &lt;= i &lt;= n. Vì có rất nhiều dãy số B\[\] thỏa mãn, nên bạn cần tìm được dãy số có tổng các phần tử là nhỏ nhất.

**Input**

- Dòng đầu tiên là số lượng bộ test T (1 &lt;= T &lt;= 10).
- Mỗi test bắt đầu bằng số nguyên N (2 &lt;= N &lt;= 1000).
- Dòng tiếp theo gồm N số nguyên A\[i\] (1 &lt;= A\[i\] &lt;= 10 000).
 
**Output**

- Với mỗi test in ra dãy số B\[\] trên một dòng.
 
**Test ví dụ:**

 | Input | Output |
|---|---|
| 2  3  1 2 3  3  5 10 5 | 1 2 3 6  5 10 10 5 |

### CP01018 - TRỘN DÃY SỐ

Cho dãy số A có N phần tử và dãy số B có M phần tử, các phần tử của hai dãy số là riêng biệt. Một cách trộn 2 dãy số A và B thành dãy số C mới có M+N phần tử được chấp nhận nếu như dãy A là một dãy con của C và B cũng là một dãy con của C. Nói cách khác, phép trộn chỉ cho phép đan xen các phần tử của 2 dãy số vào với nhau, chứ không được làm thay đổi thứ tự như trong dãy số ban đầu của chúng.

Ví dụ 2 dãy A = \[1, 2, 3\], B = \[4, 5, 6\]. Phép trộn \[1, 4, 2, 3, 5, 6\] là thỏa mãn, trong khi đó \[1, 4, 3, 2, 5, 6\] là không thỏa mãn, do đã đổi vị trí của số 2 và 3.

Cho biết N và M. Các bạn hãy xác định xem có bao nhiêu cách trộn dãy số thỏa mãn? In ra đáp án theo modulo 10^9+7.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test gồm 2 số nguyên N và M (1 ≤ N, M ≤ 100).
 
**Output:**

- Với mỗi test, in ra một số nguyên là đáp án tìm được trên một dòng.
 
**Test ví dụ:**

 | Input | Output |
|---|---|
| 2  2 2  3 2 | 6  10 |

**Giải thích test 1:**

Giả sử dãy số là \[1, 2\] và \[3, 4\]. Có 6 cách trộn 2 dãy đó là:

\[1, 2, 3, 4\], \[1, 3, 2, 4\], \[3, 4, 1, 2\], \[3, 1, 4, 2\], \[1, 3, 4, 2\], \[3, 1, 2, 4\].

### CP01019 - CHỌN BÀI

Có N quân bài trên bàn, mỗi quân bài có gán nhãn A\[i\], có nghĩa là nếu như bạn muốn bốc quân bài này, bạn phải bốc ít nhất A\[i\] quân bài khác trước đó. Giả sử một quân bài có nhãn bằng 3, trong khi trên tay bạn chỉ có 2 quân bài từ 2 lượt bốc trước, bạn không thể bốc quân bài này được.

Nhiệm vụ của bạn là hãy xác định xem có bao nhiêu cách để bốc được N quân bài? 2 cách bốc được coi là khác nhau nếu như tồn tại một lượt mà 2 quân bốc được là khác nhau.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test bắt đầu bằng số nguyên N (1 ≤ N ≤ 50000).
- Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ N).
 
**Output:**

- Với mỗi test, in ra đáp án theo modulo 10^9+7.
 
**Test ví dụ:**

 | Input | Output |
|---|---|
| 3  3  0 0 0  3  0 0 1  3  0 3 3 | 6  4  0 |

Giải thích test 1: 6 hoán vị đều thỏa mãn.

Giải thích test 2: Có 4 cách thỏa mãn là (1, 2, 3), (2, 1, 3), (1, 3, 2), (2, 3, 1).

### CP01020 - LẤY BỚT QUÂN CƠ

Trên bàn có C quân cờ. Có hai đối thủ chơi lần lượt. Mỗi lượt, người chơi sẽ lấy khỏi bàn từ 1 đến M quân cờ. Người thắng cuộc là người lấy được quân cờ cuối cùng.

Biết rằng hai người chơi đều chơi tối ưu. Hãy xác định xem ai là người thắng cuộc?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 1000).

Mỗi test gồm 2 số nguyên C và M (0 &lt;= C &lt;= 1000, 1 &lt;= M &lt;= 1000).

**Output:**

In ra “First” nếu người đi trước là người chiến thắng, in ra “Second” nếu người chơi sau là người chiến thắng.

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 4  20 9  1 5  7 5  0 3 | Second  First  First  Second |

### CP01021 - TRỪ DẦN

Cho dãy số A\[\] và dãy số B\[\] có N phần tử. Có hai đối thủ chơi lần lượt. Mỗi lượt chơi, người chơi sẽ chọn số thứ i (A\[i\]) và một số nguyên x thỏa mãn 1 &lt;= x &lt;= B\[i\], sau đó trừ A\[i\] đi x đơn vị.

Khi giá trị A\[i\] = 0 thì không được chọn i nữa.

Người thắng cuộc là có nước đi cuối cùng.

Biết rằng hai người chơi đều chơi tối ưu. Hãy xác định xem ai là người thắng cuộc?

Input:

Dòng đầu tiên là số lượng bộ test T (T &lt;= 1000).

Mỗi test bắt đầu bởi số nguyên N(1 &lt;= N &lt;= 1000).

Dòng tiếp theo gồm N số nguyên A\[i\] (0 &lt;= A\[i\] &lt;= 10^6).

Dòng cuối gồm N số nguyên B\[i\] (1 &lt;= B\[i\] &lt;= 10^6).

Output:

In ra “First” nếu người đi trước là người chiến thắng, in ra “Second” nếu người chơi sau là người chiến thắng.

Test ví dụ:

 | Input: | Output |
|---|---|
| 2  1  20  6  2  8 18  3 5 | First  Second |

### CP01022 - TRÒ CHƠI VỚI CÁC QUÂN BÀI

Có 3 cọc lần lượt chứa a, b, c quân bài. Hai người chơi lần lượt theo quy tắc như sau: mỗi bước, chọn một cọc tùy ý và được phép lấy bớt quân từ cọc này (lấy bao nhiêu cũng được, từ một cho đến toàn bộ quân). Người chiến thắng là người lấy được quân cuối cùng.

Biết rằng hai người chơi đều chơi tối ưu. Hãy xác định xem ai là người thắng cuộc?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 1000).

Mỗi test gồm 3 số nguyên a, b, c (0 &lt;= a, b, c &lt;= 1000).

**Output:**

In ra “First” nếu người đi trước là người chiến thắng, in ra “Second” nếu người chơi sau là người chiến thắng.

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 2  5 7 9  4 12 8 | First  Second |

### CP01024 - TUNG XÚC XẮC

Cho một quân xúc xắc có 6 mặt. Giả sử xác suất tung được mặt có điểm số 1 đến 6 đều bằng nhau. Với cặp số nguyên dương n và s, bạn hãy tính xem có bao nhiêu cách tung quân xúc sắc n lần để có số điểm bằng s.

**Input**

- Dòng đầu tiên ghi số bộ test (không quá 100)
- Mỗi bộ test ghi 2 số n và s trên một dòng (1 ≤ n ≤ 20; 1 ≤ s ≤ 120)
- Dữ liệu vào đảm bảo luôn có ít nhất một cách tung xúc xắc thỏa mãn.
 
**Output**

Với mỗi bộ test, ghi ra số cách tính được trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  2 5 | 4 |

**Giải thích test:**

Ta có 4 cách là :

\+ Lần 1 được 1, lần 2 được 4

\+ Lần 1 được 2, lần 2 được 3

\+ Lần 1 được 3, lần 2 được 2

\+ Lần 1 được 4, lần 2 được 1

### CP01025 - DI CHUYỂN ROBOT

Một robot xuất phát từ vị trí (0,0) mặt quay về hướng Bắc. Mỗi lần chỉ có một trong 4 lệnh chuyển động là G, L, R, B tương ứng là tiến về phía trước, tiến sang trái, tiến sang phải, lùi lại phía sau một đơn vị.

Cho dãy lệnh chuyển động. Hãy tính xem vị trí cuối cùng của robot là vị trí nào?

**Input**

- Dòng đầu tiên ghi n (n≤100) là số lệnh robot cần thực hiện.
- Dòng thứ hai là dãy n ký tự mô tả dãy lệnh robot thực hiện
 
**Output**

Ghi ra hai số nguyên là tọa độ (x,y) của vị trí cuối cùng robot

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  GLLRB | -1 0 |
| **Input** | **Output** |
| 2  RG | -2 0 |

### CP01026 - DI CHUYỂN TRÊN ĐƯỜNG THẲNG

Xét việc di chuyển từ điểm nguyên này tới điểm nguyên khác trên đường thẳng theo quy tắc sau:

- Bắt đầu từ một điểm có toạ độ nguyên,
- Từ điểm hiện tại tới điểm mới với bước đi không âm, độ dài bằng bước đi trước hoặc khác 1 đơn vị.
 
**Yêu cầu:** Cho 2 số nguyên x và y (0 ≤ x ≤ y ≤ 231). Hãy xác định số bước tối thiểu đi từ x tới y với với bước đi ban đầu và bước đi cuối cùng đều có độ dài 1.

 Ví dụ, với x = 45, y = 40, số bước di chuyển tối thiểu là 4:

45 -&gt; 46 -&gt; 48 -&gt; 49 -&gt; 50

![](data:image/png;base64,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)

**Input**

Gồm nhiều dòng, mỗi dòng ghi hai số x, y

**Output**

Mỗi dòng ghi kết quả của bộ test tương ứng

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 0 6  14 19  2 5 | 4  4  3 |

### CP01028 - TÍCH NHỎ NHẤT

Bạn được cung cấp 4 số nguyên dương a,b,x,y. Ban đầu a ≥ x và b ≥ y. Bạn có thể thực hiện thao tác dưới đây không quá n lần:

*Chọn a hoặc b và giảm giá trị cúa nó đi 1, tuy nhiên kết quả của thao tác này phải thỏa mãn a ≥ x và b ≥ y.*

Nhiệm vụ của bạn là tìm ra tích nhỏ nhất có thể có của a và b (a.b) bằng cách sử dụng các thao tác trên một cách tối ưu và không quá n lần.

**Input:**

- Đầu vào là chứa một số nguyên T (1≤ T ≤ 2.104) – số trường hợp thử nhiệm.
- T dòng tiếp theo chứa năm số nguyên dương a,b,x,y,n (1 ≤ a,b,x,y,n ≤ 109) .
 
**Output:**

- Với mỗi thử nhiệm hãy in ra một số nguyên: tích nhỏ nhất có thể có của a và b.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  10 10 8 5 3  12 8 8 7 2  12343 43 4543 39 123212  10 11 2 1 5  10 11 9 1 10 | 70  77  177177  55  10 |

**Giải thích:**

- Test 1: bạn cần giảm b 3 lần và được 10.7 = 70.
- Test 2: bạn cần giảm a và b 1 lần và được 11.7 = 77.
- Test 4: bạn cần giảm a 5 lần và được 5.11 = 55.
- Test 5: bạn cần giảm b đi 10 lần và được 10.1 = 10.

### CP01029 - BỐC BI

Unnie có một hộp bi trong đó có a viên bi màu đỏ, b viên bi màu xanh và c viên bi màu vàng. Unnie đố Oppa có thể nhắm mắt mà lấy ra được k viên bi có cùng màu.

Oppa vừa đi dép lê vừa suy nghĩ nhưng mà không biết phải làm như thế nào. Nhờ các bạn tính giúp xem Oppa cần lấy ít nhất bao nhiêu viên để đảm bảo yêu cầu của Unnie nha.

**Input**

Chứa 4 số nguyên a, b, c, k. (1 ≤ a, b, c ≤ 1000, 1 ≤ k ≤ max(a, b, c))

**Output**

In ra 1 số nguyên là đáp án của bài toán.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2 4 6 3 | 7 |

**Giải thích:** nếu chỉ lấy 6 viên thì sẽ có khả năng là 2 bi xanh + 2 bi đỏ + 2 bi vàng.

### CP02013 - DÃY SỐ ĐỘC ĐẮC

Cho dãy số A\[\] có N phần tử. Một dãy con X chứa các phần tử liên tiếp của A\[\] được gọi là “độc nhất”, nếu như tồn tại một phần tử xuất hiện duy nhất đúng một lần trong X.

Dãy số A\[\] được gọi là “độc đắc” nếu như mọi dãy con liên tiếp có độ dài nhỏ hơn N đều là dãy số độc nhất. Nhiệm vụ của bạn là xác định xem dãy số đã cho có phải là độc đắc hay không?

**Dữ liệu vào:**

Dòng đầu tiên là số lượng bộ test T (không quá 20).

Mỗi test gồm số đầu tiên là số lượng phần tử N (2&lt;=N&lt;=100000)

Dòng tiếp theo gồm N số nguyên không âm A\[i\], có giá trị không vượt quá 109.

**Kết quả:**

Với mỗi test, hãy in ra đáp án tìm được trên một dòng. Nếu dãy số là độc đắc, in ra “YES”. In ra “NO” trong trường hợp ngược lại.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5  5  1 2 3 4 5  7  1 2 3 4 3 4 1  5  1 1 1 1 1  5  1 2 5 2 1  5  5 5 2 5 5 | YES  NO  NO  YES    NO |

### CP02014 - BIỂU THỨC

Cho dãy số a\[\] gồm có N phần tử. Nhiệm vụ của bạn là xác định nhóm chỉ số 1&lt;=i1&lt;i2&lt;...&lt;i5K&lt;=N sao cho biểu thức dưới đây đạt giá trị lớn nhất.

![](data:image/png;base64,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)

**Dữ liệu vào:**

Dòng đầu tiên là số lượng bộ test T (không quá 10).

Mỗi test bắt đầu bởi hai số nguyên N và K. (0&lt;=5K&lt;=N&lt;=1000).

Dòng tiếp theo mô tả dãy số (các phần tử không quá 10^9).

**Kết quả:**

Với mỗi test, in ra giá trị lớn nhất của biểu thức S.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5 1  1 2 3 4 5  6 1  1 2 3 -3 -2 -1 | 15  13 |

### CP02015 - CHIA HẾT

Cho dãy số {a\_1, a\_2, …, a\_n} và m dãy số {b\_1, b\_2, …, b\_n}.

Với mỗi truy vấn, bạn cần trả lời xem tích a\_1\*a\_2\*…\*a\_n có chia hết cho b\_1\*b\_2\*…\*b\_n hay không?

**Input:**

Dòng đầu tiên là hai số nguyên n và m (n, m ≤ 100).

Dòng tiếp theo gồm n số nguyên a\[i\].

M dòng tiếp, mỗi dòng là một truy vấn gồm n số nguyên b\[i\]. Các số có giá trị không vượt quá 10^15.

**Output:**

Dòng đầu tiên in ra số bộ dãy số b\[\] thỏa mãn. Dòng thứ 2 in ra lần lượt bộ dãy số thứ i thỏa mãn yêu cầu.

**Ví dụ:**

 | Input | Output |
|---|---|
| 3 4  7 10 2011  1 3 5  2 2 7  7 2 5  14 1 2011 | 2  3 4 |

### CP02017 - NGÂN HÀNG

Một ngân hàng muốn dành ra N đồng để cho sinh viên vay vốn ưu đãi và có m sinh viên đăng ký, sinh viên thứ i đăng ký vay ti đồng. Ngân hàng muốn đáp ứng được nhiều sinh viên nhất nhưng phải đảm bảo nếu sinh viên thứ i được cho vay thì phải vay đúng ti đồng.

Trong các cách thỏa mãn, ngân hàng muốn chọn cách mà số sinh viên vay ít nhất là lớn nhất.

**Yêu cầu:** Cho t1,t2,…,tm và lần lượt Q giá trị N giả định.

Với mỗi giá trị N, hãy đưa ra cách cho vay thỏa mãn yêu cầu đề bài.

**Input**

Dòng đầu ghi 2 số m và Q (m,Q ≤ 9000).

Dòng thứ 2 ghi m số nguyên dương t1 … tm (0 &lt; ti ≤ 109)

Dòng thứ 3 ghi Q giá trị N giả định (0 &lt; Ni ≤ 1018)

**Output**

Gồm Q dòng, mỗi dòng ghi 2 số s,v lần lượt là số sinh viên được vay vốn và số tiền sinh viên được vay ít nhất ứng với giá trị N giả định.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 2  1 3 2 3 5  6 8 | 3 1  3 2 |

### CP02023 - ĐẢO DẤU

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

### CP02024 - GIÁ TRỊ LỚN NHẤT

Cho dãy số A có N phần tử, đánh số từ 1 đến N. Mỗi lần loại một vị trí i ra khỏi dãy (1 &lt; i &lt; N) thì ta sẽ có thêm một giá trị được tính bằng tích của A\[i-1\] \* A\[i+1\]. Sau đó các số còn lại trong dãy lại được đánh số lại từ đầu.

Dễ dàng nhận thấy ta sẽ không thể lấy ra được hai số đầu và cuối dãy nên khi chỉ còn hai số này thì sẽ kết thúc.

Hãy tính tổng giá trị lớn nhất có thể thu được.

**Input**

Dòng đầu tiên ghi số N (3 ≤ N ≤ 100)

Dòng tiếp theo ghi N số của dãy A (1 ≤ A\[i\] ≤ 1000)

**Output**

Ghi ra tổng giá trị lớn nhất có thể đạt được.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  1 2 3 4 | 12 |

### CP03001 - MA TRẬN XOẮN ỐC

Ma trận xoắn ốc cấp N là một ma trận vuông cấp N\*N trong đó ghi các số nguyên dương tăng dần từ 1 đến N\*N được điền theo thứ tự xoắn ốc từ ngoài vào trong.

Hãy viết chương trình in ra ma trận xoắn ốc cấp N.

**Input:**

Chỉ có một dòng ghi số N (1 ≤ N ≤ 100)

**Ouput:**

Ghi ra ma trận kết quả có N dòng, mỗi giá trị số cách nhau một khoảng trống.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5 | 1 2 3 4 5  16 17 18 19 6  15 24 25 20 7  14 23 22 21 8  13 12 11 10 9 |

### CP03005 - MA TRẬN ĐƠN VỊ

Cho ma trận đơn vị A\[\]\[\] (chỉ có các giá trị 0,1) có kích thước *N*x*M*. Nhiệm vụ của bạn là hãy đếm số lượng ma trận đơn vị con của A\[\]\[\] có tổng các phần tử bằng *K* cho trước.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm số nguyên *N*, *M* và *K (3 ≤ N, M ≤ 1000; 1 ≤ K ≤ 4)* .

*N* dòng tiếp theo, mỗi dòng gồm một xâu có độ dài bằng M, mô tả một hàng của ma trận.

**Output:**

Với mỗi test, in ra số lượng hình chữ nhật có tổng bằng *K* tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5 5 4  01010  10101  01010  10101  01010  4 4 4  1111  1111  1111  1111 | 21  17 |

### CP03018 - CHIA HẾT

Cho 2 dãy số nguyên dương A\[\]và B\[\] cùng có N phần tử. Hãy kiểm tra xem tích các phần tử của dãy A\[\] có chia hết cho tích các phần tử của dãy B\[\] hay không.

**Input:**

Dòng đầu tiên là hai số nguyên N và M.

Dòng tiếp theo gồm n số nguyên A\[i\].

M dòng tiếp, mỗi dòng là một truy vấn gồm N số nguyên B\[i\].

**Output:**

Dòng đầu tiên in ra số bộ dãy số B\[\] thỏa mãn. Dòng thứ 2 ghi lần lượt thứ tự các dãy số B\[\] thỏa mãn yêu cầu (tính từ 1 đến M).

***Giới hạn:***

(1) Có 50% số test ứng với N, M ≤ 10. Các số A\[i\], B\[i\] có giá trị không vượt quá 106.

(2) Có 50% số test ứng với N, M ≤ 100. Các số A\[i\], B\[i\] có giá trị không vượt quá 1015.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3 4  7 10 2011  1 3 5  2 2 7  7 2 5  14 1 2011 | 2  3 4 |

### CP03019 - TÔ MÀU KHỐI LẬP PHƯƠNG

Bạn có 1 khối lập phương và N loại màu sơn. Cho trước số lượng mỗi loại màu sơn, hãy đếm số cách tô màu lên hình lập phương sao cho mỗi mặt chung một cạnh có màu khác nhau.

Hai cách tô màu được coi là giống hệt nhau nếu một khối có thể xoay ra khối còn lại.

**Input:**

Dòng đầu tiên chứa một số nguyên N (1 ≤ N ≤ 1000), số lượng các loại sơn.

Dòng thứ hai chứa N các giá trị nguyên dương không quá 106, đại diện cho số lượng của mỗi loại màu.

**Output:**

Một dòng duy nhất in ra kết quả của bài.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 8  1 1 1 1 1 1 1 2 | 945 |

### CP03020 - ĐẾM ƯỚC SỐ CỦA C(K,N)

Cho hai số nguyên dương n và k. Hãy đếm số ước số khác nhau của tổ hợp chập k của n phần tử.

**Input:**

Dữ liệu vào gồm nhiều dòng, mỗi dòng ghi hai số nguyên dương n và k (0 ≤ k ≤ n ≤ 431). (chú ý: không có dòng ghi số bộ test, cần tự đọc đến hết các dòng của luồng vào).

**Output:**

Ghi ra kết quả trên một dòng. Dữ liệu vào đảm bảo kết quả không vượt quá 263 – 1.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5 1  6 3  10 4 | 2  6  16 |

### CP03021 - CHỮ SỐ 0

Cho số nguyên dương N, hãy tìm số nguyên M nhỏ nhất sao cho M! có đúng N chữ số 0 ở cuối.

**Input**

Dòng đầu ghi số bộ test, không quá 105

Mỗi bộ test ghi một số N (1 ≤ N ≤ 1016)

**Output**

Với mỗi bộ test đưa ra trên một dòng giá trị M tính được.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  1  3 | 5  15 |

### CP03022 - SỐ PHẢN NGUYÊN TỐ

Số nguyên dương N được gọi là phản nguyên tố nếu như số lượng ước số của N lớn hơn số lượng ước số của tất cả các số nguyên dương nhỏ hơn N.

Ví dụ các số phản nguyên tố đầu tiên: 1, 2, 4, 6, 12, 24, …

Cho số nguyên dương X, hãy tìm số phản nguyên tố bé nhất không nhỏ hơn X.

**Input:**

Dòng đầu ghi số bộ test T (không quá 106)

Mỗi test ghi số nguyên dương X (1 ≤ X ≤ 107)

**Output:**

Với mỗi test, ghi ra kết quả tính được trên một dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  5 | 6 |

### CP03023 - DÃY SỐ HAMMING

Dãy số nguyên dương tăng dần trong đó ước số nguyên tố lớn nhất của các số trong dãy đều không vượt quá 5 được gọi là dãy số Hamming. Ví dụ 10 = 2x5 thuộc dãy Hamming còn 26 = 2x13 không thuộc dãy Hamming.

Số 1 được coi là số đầu tiên của dãy Hamming.

Cho số nguyên dương N. Hãy xác định xem N có thuộc dãy Hamming hay không và nếu có thì thứ tự của N trong dãy Hamming là bao nhiêu.

**Input:**

Dòng đầu tiên ghi số bộ test (không quá 105).

Mỗi test ghi một số N (1 ≤ N ≤ 1018).

**Output:**

Nếu giá trị N thuộc dãy Hamming thì ghi ra thứ tự của N (tính từ 1).

Nếu không thì ghi ra “Not in sequence”

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 11  1  2  6  7  8  9  10  11  12  13  14 | 1  2  6  Not in sequence  7  8  9  Not in sequence  10  Not in sequence  Not in sequence |

### CP03024 - CHIA HẾT CHO 7

Cho một số nguyên dương N. Mỗi bước bạn thực hiện tính tổng của N với giá trị số đảo ngược của N. Bạn sẽ dừng lại khi gặp giá trị chia hết cho 7 hoặc khi đã thực hiện quá 1000 bước lặp.

Hãy tính giá trị chia hết cho 7 tìm được theo thủ tục trên hoặc ghi ra -1 nếu không thể tìm ra đáp án.

**Input:**

Dòng đầu ghi số bộ test (không quá 1000).

Mỗi test ghi số N (1 ≤ N ≤ 1018)

**Output:**

Ghi ra giá trị chia hết cho 7 đầu tiên tìm được. Hoặc số -1 nếu không thể tìm được đáp án.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5  1  2  3  4  999999 | 77  77  9447438  77  999999 |

Giải thích test 1: 1 à 2 à 4 à 8 à 16 à 77

### CP03027 - ĐẾM ƯỚC SỐ CỦA BỘI SỐ CHUNG NHỎ NHẤT

Gọi số X là **bội chung nguyên dương nhỏ nhất** của các số nguyên liên tiếp từ 1 đến N. Viết chương trình nhập N và đếm số lượng ước nguyên dương của X.

**Input**

Dòng đầu tiên ghi số bộ test (không quá 50).

Mỗi test ghi số N (1 ≤ N ≤ 105).  
 **Output**

Với mỗi test, ghi ra kết quả trên một dòng, chia dư cho 109 + 7

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  4  6 | 6  12 |

### CP03031 - GHÉP HÌNH CHỮ NHẬT

Cho ba hình chữ nhật. Các bạn được phép xoay hình nhưng không được phép xếp chồng lấn lên nhau, hỏi 3 hình chữ nhật đó có thể ghép thành một hình vuông được hay không

**Input:** Có ba dòng, mỗi dòng ghi hai số nguyên dương là chiều rộng và chiều cao của hình chữ nhật (các số đều không quá 100).

**Output:** Ghi ra YES nếu có thể tạo thành hình vuông, NO nếu không thể.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 8 2  1 6  7 6 | YES |

### CP03032 - DIỆN TÍCH TAM GIÁC - 1

Cho 3 điểm A, B, C trong không gian 2 chiều Oxy, hãy tính diện tích tam giác được tạo bởi 3 điểm đó.

*Công thức Heron tính diện tích tam giác khi biết độ dài 3 cạnh là a,b,c:*

*![](data:image/png;base64,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)*

**Input**

- Dòng đầu ghi số bộ test, không quá 10
- Mỗi bộ test ghi trên 1 dòng 6 số thực có giá trị tuyệt đối không quá 1000 lần lượt là tọa độ của 3 điểm A, B, C.
 
**Ouput**

- Nếu 3 điểm không thể tạo thành tam giác thì in ra INVALID
- Nếu 3 điểm tạo thành 1 tam giác thì in ra diện tích của tam giác đó, làm tròn đến 2 chữ số phần thập phân.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  0 0 0 5 0 199  1 1 1 1 1 1  0 0 0 5 5 0 | INVALID  INVALID  12.50 |

### CP03033 - DIỆN TÍCH TAM GIÁC - 2

Cho tam giác ABC và điểm D nằm trên cạnh AB (khác 2 đầu mút). Bạn hãy tìm điểm E nằm trên cạnh AC sao cho diện tích tam giác ABC gấp K lần diện tích tam giác ADE.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm bắt đầu bởi số nguyên K.

Dòng tiếp theo gồm 8 số nguyên mô tả tọa độ các điểm A, B, C, D. Các tọa độ có giá trị tuyệt đối không vượt quá 1000.

**Output:**

Với mỗi test in ra tọa độ điểm E tìm được, với độ chính xác 2 chữ số sau dấu phảy. Nếu không tìm được đáp án, in ra “No solution”.

**Ví dụ:**

 | **Input** | **Output:** |
|---|---|
| 2  4  2 2 0 0 4 0 1 1  2  0 5 0 0 5 0 0 4 | 3.00 1.00  No solution |

### CP03035 - BỐN ĐIỂM TRÊN MẶT PHẲNG

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

### CP03036 - DIỆN TÍCH ĐA GIÁC

Cho một đa giác lồi có N đỉnh trên mặt phẳng Oxy. Nhiệm vụ của bạn là hãy tính diện tích đa giác này.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 100).

Mỗi test bắt đầu bởi số nguyên N (N ≤ 1000).

N dòng tiếp theo, mỗi dòng gồm 2 số nguyên x\[i\], y\[i\] (-1000 ≤ x\[i\], y\[i\] ≤ 1000) là tọa độ của điểm thứ i. Các điểm được liệt kê theo thứ tự ngược chiều quay kim đồng hồ.

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

 | Input: | Output |
|---|---|
| 2  3  0 0  1 0  0 1  4  0 0  2 0  2 2  0 2 | 0.500  4.000 |

### CP04001 - ĐỔI TIỀN

Có n tờ tiền có giá trị t\[1\], t\[2\], …, t\[n\]. Hãy tìm cách trả ít tờ tiền nhất với số tiền đúng bằng S (các tờ tiền có giá trị bất kỳ và có thể bằng nhau, mỗi tờ tiền chỉ được dùng một lần).

**Input**

Mỗi bộ test gồm 2 số nguyên n và S (n ≤ 30; S ≤ 109).

Dòng thứ hai chứa n số nguyên t\[1\], t\[2\], …, t\[n\] (t\[i\] ≤ 109)

**Output:**

Ghi ra trên một dòng số tờ tiền ít nhất phải trả.

Nếu không thể tìm được kết quả, in ra -1.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3 5  1 4 5 | 1 |

### CP04002 - KÝ TỰ LẶP

Cho một dãy các xâu ký tự chỉ bao gồm các chữ cái in hoa từ A đến Z, trong đó các ký tự trong mỗi xâu đều đã được sắp xếp theo thứ tự từ điển và mỗi chữ cái chỉ xuất hiện nhiều nhất một lần (tức là độ dài xâu tối đa là 26). Nếu một ký tự xuất hiện trong hai xâu liên tiếp thì được coi là một lần lặp. Hãy tìm cách sắp xếp lại thứ tự các xâu sao cho số lần lặp là nhỏ nhất có thể. Ví dụ dưới đây là cùng một dãy xâu nhưng với cách sắp xếp lại thì số lần lặp chỉ còn 2.

ABC  
 ABEF  
 DEF  
 ABCDE  
 FGH

=&gt; Số lần lặp là 6

ABEF  
 DEF  
 ABC  
 FGH  
 ABCDE

=&gt; Số lần lặp là 2.

**Input**

Dòng đầu tiên ghi số N (2 ≤ N ≤ 10) là số xâu ký tự. N dòng tiếp theo, mỗi dòng ghi một xâu.

**Output**

In ra trên một dòng số lần lặp nhỏ nhất có thể.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5    ABC    ABEF    DEF    ABCDE    FGH | 2 |
| 6    BDE    FGH    DEF    ABC    BDE    ABEF | 3 |
| 4    XYZ    XYZ    ABYZ    Z | 4 |

### CP04005 - CHIA ĐỀU

Cho dãy số A có N phần tử và số K. Hãy đếm số cách chia dãy A thành **K nhóm các phần tử liên tiếp** sao cho tổng giá trị của mỗi nhóm đều bằng nhau.

**Input**

Dòng đầu ghi hai số N và K (0 &lt; N ≤ 12; 0 &lt; K &lt; N ).

Dòng thứ 2 ghi N số của dãy A (-10000 ≤ A\[i\] ≤ 10000)

**Output**

In ra số cách thỏa mãn

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3 2  -2 0 -2 | 2 |
| 3 2  1 2 3 | 1 |

### CP04007 - BÀN CỜ

Một bàn cờ có dạng bảng vuông kích thước 4 \* 4, trên đó có một số quân cờ. Một quân cờ chỉ có thể di chuyển sang 1 ô kề cạnh còn trống, mỗi di chuyển như vậy được gọi là 1 bước di chuyển.

Cho hai trạng thái của bàn cờ, hãy chỉ ra một dãy các bước di chuyển để đưa bảng từ trạng thái xuất phát đến trạng thái đích với số phép di chuyển là ít nhất. Mỗi trạng thái được mô tả là một ma trận 4 \* 4 trong đó số ô ở hàng i, cột j là 1 nếu tại vị trí (i,j) tương ứng có quân cờ đang đứng hoặc bằng 0 nếu không có.

**Input**

- Gồm 2 \* 4 dòng thể hiện ma trận mô tả trạng thái xuất phát và trạng thái đích. 4 dòng đầu tiên thể hiện ma trận xuất phát, 4 dòng tiếp theo là ma trận đích.
- Input luôn đảm bảo là có nghiệm.
 
**Output**

- Dòng đầu tiên ghi k là số ít nhất các phép biến đổi tìm được.
- K dòng tiếp, mỗi dòng mô tả 1 phép biến đổi, theo đúng trình tự biến đổi, gồm 4 số nguyên dương u, v, x, y thể hiện di chuyển quân cờ ở vị trí (u, v) sang vị trí (x, y).
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1111  1111  0000  0000  0000  0000  1111  1111 | 16  2 1 3 1  1 1 2 1  2 2 3 2  1 2 2 2  2 3 3 3  1 3 2 3  2 4 3 4  1 4 2 4  3 1 4 1  2 1 3 1  3 2 4 2  2 2 3 2  3 3 4 3  2 3 3 3  3 4 4 4  2 4 3 4 |

### CP04011 - SỐ NHỎ NHẤT

Cho hai số nguyên dương S và D. Hãy tìm số nguyên dương N nhỏ nhất thỏa mãn S là tổng các chữ số của N và D là số các chữ số của N?

Ví dụ với S = 9, D = 2 ta có số nhỏ nhất thỏa mãn S và D là N = 18.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là bộ 2 số S và D được viết trên một dòng.
- T, S, D thỏa mãn ràng buộc: 1≤T≤100; 1≤ S,D≤1000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng. Nếu không có đáp án, in ra -1.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    9 2    20 3 | 18    299 |

### CP04012 - GIÁ TRỊ NHỎ NHẤT CỦA XÂU

Cho xâu ký tự S. Ta gọi giá trị của xâu S là tổng bình phương số lần xuất hiện mỗi ký tự trong S. Hãy tìm giá trị nhỏ nhất của xâu S sau khi thực hiện K lần loại bỏ ký tự.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất là số K; phần thứ hai là một xâu ký tự S được viết trên một dòng.
- T, S, K thỏa mãn ràng buộc: 1≤T≤100; 1≤length(S)≤10000; 1≤K≤1000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    2  ABCCBC    2  AAAB | 6    2 |

### CP04013 - TÍCH LỚN NHẤT

Cho dãy số A gồm N phần tử là các số nguyên. Hãy tính tích lớn nhất của **2 hoặc 3** phần tử trong dãy.

**Input**

Dòng đầu tiên ghi số N (3 ≤ N ≤ 10000)

Dòng thứ 2 ghi N số của dãy A (|Ai| ≤ 1000)

**Outpput**

Ghi ra kết quả trên một dòng

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 6  5 10 -2 3 5 2 | 250 |

### CP04015 - DÃY SỐ

Cho dãy số nguyên A\[\] gồm có N phần tử. Nhiệm vụ của bạn là tìm dãy số B\[\] có tổng phần tử nhỏ nhất thỏa mãn tính chất A\[i\] **/** B\[i\] = A\[i+1\] **/** B\[i+1\] với mọi chỉ số i (0 ≤ i ≤ N-2).

Phép chia trong bài toán này là phép chia nguyên (tức là chỉ lấy phần nguyên của kết quả: ví dụ 5/3 = 1).

**Input:**

Dòng đầu tiên là số lượng phần tử N (1 ≤ N ≤ 1000).

Dòng tiếp theo gồm N số nguyên A\[i\] (1 ≤ A\[i\] ≤ 2000).

**Output:**

In ra một số nguyên là tổng các phần tử của dãy số B\[\] tìm được.

**Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 5  18 27 16 22 6 | 25 |

*Giải thích test: Dãy B\[\] tìm được là 5, 7, 5, 6, 2.*

### CP04018 - XẾP NHÓM

Có N quốc gia, mỗi quốc gia có dân số xác định. Hãy xác định có thể xếp được tối đa bao nhiêu nhóm có đúng k thành viên mà các thành viên từ các nước khác nhau.

**Input:**

Gồm nhiều test (không quá 20), mỗi test có định dạng như sau:

Dòng đầu tiên chứa số nguyên N và k(1 ≤ k ≤ N ≤ 105):

Dòng tiếp theo chứa N số nguyên không âm là dân số từng nước, các giá trị này không vượt quá 1012

**Ouput**

Với mỗi test, in ra 1 số nguyên là đáp án của bài toán.

**Ví dụ:**

 | **INPUT** | **OUTPUT** |
|---|---|
| 5  5 4  4 4 4 4 4  6 5  1 2 3 4 5 6  2 2  1000000000000 1000000000000  17 7  96 17 32 138 112 50 7 19 412 23 14 50 47 343 427 22 39  50 10  638074479 717901019 910893151 924124222 991874870 919392444 729973192 607898881 838529741 907090878 632877562 678638852 749258866 949661738 784641190 815740520 689809286 711327114 658017649 636727234 871088534 964608547 867960437 964911023 642411618 868318236 793328473 849540177 960039699 998262224 775720601 634685437 743766982 826321850 846671921 712570181 676890302 814283264 958273130 899003369 909973864 921987721 978601888 633027021 896400011 725078407 662183572 629843174 617774786 695823011 | 5  3  1000000000000  166  3983180234 |

### CP04024 - ĐẦU TƯ BITCOIN

Xu hướng đầu tư bitcoin kiếm lời đang lan rộng. Thay vì hướng dẫn cách chơi, Học viện Hoàng Gia lại ra đề bài để thử thách khả năng tính toán tối ưu của sinh viên.

Biết trước giá bitcoin trong N ngày, và giả sử đang có 1 coin. Hãy tính toán lợi nhuận lớn nhất có thể thu được nếu bán đồng coin đó vào một ngày nào đó, sau đó mua lại chính đồng coin đó trong một ngày nào đó sau đó.

Chú ý: không được vừa mua vừa bán trong 1 ngày. Và chỉ mua bán một lần duy nhất.

**Input**

Dòng 1 ghi số N.

Dòng tiếp theo ghi N số nguyên dương lần lượt là giá của đồng bitcoin trong N ngày (các giá trị không quá 100).

**Output**

Ghi ra giá trị lợi nhuận lớn nhất.

Hoặc nếu không thể có lợi nhuận thì ghi ra **“Lo nang roi!”**

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  1 3 2 | 1 |

**Ràng buộc:**

*40% test tương ứng với 1 ≤ N ≤ 1000*

*60% test tương ứng với 1 ≤ N ≤ 100000*

### CP04027 - TRÒ CHƠI

Tí đang chơi một trò chơi với N quân bài, mỗi quân bài được đánh dấu bằng một số nguyên a\[i\]. Mỗi lượt chơi, Tí chọn ngẫu nhiên 2 quân bài X và Y kề nhau, loại bỏ chúng rồi thay bằng một quân bài mới có giá trị bằng tổng của 2 quân bài đã chọn. Số điểm mà Tí nhận được thêm là X+Y.

Trò chơi sẽ kết thúc sau N-1 lượt. Các bạn hãy xác định xem số điểm trung bình mà Tí nhận được bằng bao nhiêu?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test bắt đầu bởi số nguyên dương N (2 ≤ N ≤ 2000).

Dòng tiếp theo gồm N số nguyên a\[i\] (1 ≤ a\[i\] ≤ 10^9).

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng với độ chính xác 6 chữ số sau dấu phảy.

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 2  3  2 1 8  5  10 3 70 2 21 | 17.000000  288.750000 |

Giải thích test 1:

Nếu Tí chọn (2, 1) sẽ thu được (3, 8) và có 3 điểm đầu tiên. Bước 2 sẽ có được 11 điểm. Tổng cộng Tí có 14 điểm.

Nếu Tí chọn (1, 8) sẽ thu được (2, 9) và có 9 điểm. Sau bước 2 cũng sẽ thu được thêm 11 điểm. Tổng cộng Tí có 20 điểm.

Vậy trung bình Tí sẽ nhận được (14+20)/2 = 17 điểm.

### CP04030 - TÔ MÀU

Cho một bảng hình vuông kích thước N x N. Có tất cả N^2 màu bạn có thể dùng để vẽ.

Do bút tô màu rất đặc biệt, mỗi lượt tô, bạn sẽ tô màu cả một vùng theo hình chữ nhật. Khi tô một màu mới lên một ô đã được tô màu, màu cũ sẽ bị che phủ hoàn toàn. Ví dụ bạn có thể tô màu bảng với 3 màu như sau. Đầu tiên tô một hình vuông với màu 2.

2 2 2 0

2 2 2 0

2 2 2 0

0 0 0 0

Sau đó tô một hình chữ nhật màu 5:

2 2 2 0

2 5 5 5

2 5 5 5

0 0 0 0

Cuối cùng tô một hình chữ nhật nhỏ màu 3:

2 2 3 0

2 5 3 5

2 5 5 5

0 0 0 0

Ở phòng tập vẽ, có rất nhiều bức tranh đã được các bạn khác hoàn thiện. Nhiệm vụ của bạn là hãy xác định xem với một bức tranh, có bao nhiêu màu mà tác giả có thể đã sử dụng nó để vẽ đầu tiên?

**Input**

Dòng đầu tiên chứa số nguyên dương N (1 ≤ N ≤ 1000).

N dòng tiếp theo, mỗi dòng gồm N số, mô tả trạng thái cuối cùng của bảng màu.

**Output**

In ra số lượng màu có thể được sử dụng đầu tiên.

 | **Input:** | **Output** |
|---|---|
| 4  2 2 3 0  2 5 3 5  2 5 5 5  0 0 0 0 | 14 |

Trong ví dụ trên, ta có thể tô màu X nào đó vào trong các ô đã tô màu (X khác 2, 3, 5). Sau đó tô màu 2, tiếp tục màu 5 và cuối cùng màu 3. Tổng cộng có tất cả 14 màu có thể tô đầu tiên.

### CP04036 - ĐƯỜNG ĐI TRUNG BÌNH NGẮN NHẤT TRÊN CÂY

Cho một cây có N đỉnh, mỗi đỉnh có trọng số lần lượt bằng T\[i\]. Một đường đi từ nút gốc tới nút lá có giá trị bằng tổng trọng số các đỉnh mà nó đi qua.

Xuất phát từ nút gốc, xác suất để đi tới một nút kề cạnh nó mà chưa được thăm là bằng nhau. Ví dụ nút gốc có 5 nút con, thì xác suất đi theo mỗi con đường bằng 0.2. Như vậy, xác suất để chọn làm đích đối với mỗi nút lá là khác nhau.

Gọi EX là kì vọng của giá trị đường đi từ nút gốc tới một nút lá. Bạn hãy chọn một đỉnh làm nút gốc, sao cho giá trị EX là nhỏ nhất?

**Input:**

Dòng đầu tiên là số nguyên N (1 ≤ N ≤ 100 000).

Dòng tiếp theo gồm N số nguyên T\[i\] (1 ≤ T\[i\] ≤ 1 000 000).

N-1 dòng tiếp, mỗi dòng gồm 2 số u, v cho biết có cạnh nối giữa u và v.

**Output:**

In ra một số nguyên là đáp án của bài toán. Input đảm bảo có một đáp án duy nhất.

**Ví dụ:**

 | **Test 1** | **Test 2** |
|---|---|
| Input:  5  2 2 1 2 2  1 2  2 3  3 4  4 5  Output:  3 | Input:  5  5 7 14 14 19  2 3  4 5  4 1  1 3  Output:  1 |

Cây có dạng: 1 à 2 à 3 à 4 à 5.

Root = 1, 1à 5 giá trị bằng 9, trung bình bằng 9.

Root = 2, 2à 1 giá trị bằng 4, 2 à 5 giá trị bằng 7, trung bình bằng 5.5.

Root = 3, 3à 1 giá trị bằng 5, 3 à 5 giá trị bằng 5, trung bình bằng 5, là nhỏ nhất.

### CP04037 - THÀNH PHỐ TRỌNG ĐIỂM

Đất nước X gồm có N thành phố được kết nối với nhau bởi N-1 tuyến đường. Hệ thống giao thông đảm bảo rằng giữa 2 thành phố bất kì luôn có đường đi tới nhau. Gọi d(u,v) là khoảng cách tuyến đường giữa 2 thành phố u và v. Mỗi đợt, đất nước X nâng cấp một tuyến đường, và khoảng cách giữa 2 thành phố sẽ được thu hẹp lại.

Đất nước X muốn chọn ra 3 thành phố để làm trung tâm và phát triển trọng điểm. Chi phí cần để nâng cấp 3 thành phố c1, c2, c3 nên làm trọng điểm bằng d(c1, c2) + d(c2, c3) + d(c3, c1). Dù vẫn chỉ là kế hoạch, chưa có 3 thành phố chính thức nào được chọn, nhưng mỗi năm chính phủ đất nước X vẫn tính toán xem chi phí trung bình để xây dựng 3 thành phố trọng điểm là bao nhiêu bằng cách chọn ngẫu nhiên các thành phố. Các bạn hãy tính thử xem giá trị này bằng bao nhiêu?

**Input:**

Dòng đầu tiên là số nguyên N (3 ≤ N ≤ 100 000).

N-1 dòng tiếp, mỗi dòng gồm 3 số u\[i\], v\[i\], c\[i\] cho biết đường đi giữa thành phố u\[i\] và v\[i\] ban đầu có độ dài bằng c\[i\] (1 ≤ c\[i\] ≤ 1000).

Dòng tiếp theo là số nguyên Q (1 ≤ Q ≤ 100 000), là số đợt nâng cấp đường.

Q dòng tiếp theo, mỗi dòng gồm 2 số nguyên x và w cho biết tuyến đường thứ x được nâng cấp, và độ dài quãng đường giảm xuống còn w (1 ≤ w ≤ 1000).

**Output:**

Sau mỗi đợt nâng cấp đường, hãy in ra chi phí trung bình để xây dựng 3 thành phố trọng điểm, với độ chính xác 6 chữ số sau dấu phảy.

**Ví dụ:**

 | **Test 1** | **Test 2** |
|---|---|
| Input:  3  2 3 5  1 3 3  5  1 4  2 2  1 2  2 1  1 1  **Output:**  14.000000  12.000000  8.000000  6.000000  4.000000 | Input:  6  1 5 3  5 3 2  6 1 7  1 4 4  5 2 3  5  1 2  2 1  3 5  4 1  5 2  **Output:**  19.600000  18.600000  16.600000  13.600000  12.600000 |

Giải thích test 1:

Có 3 thành phố, vậy chi phí sẽ bằng d(1, 2) + d(2, 3) + d(3, 1). Sau khi nâng cấp, d(2, 3) = 4, vậy chi phí sau đợt nâng cấp đầu tiên là 7+4+3 = 14.

### CP04038 - CÂY NHỊ PHÂN TÌM KIẾM

Cây nhị phân tìm kiếm là một cấu trúc dữ liệu dạng cây, trong đó mỗi nút được gán một giá trị và có nhiều nhất hai nút con. Giá trị của mỗi nút luôn lớn hơn giá trị của nút con trái và nhỏ hơn giá trị của nút con phải. Nút không có nút con được gọi là nút lá. Độ cao của cây được định nghĩa là số nút trên đường đi đơn từ nút gốc tới nút lá xa nhất.

Hãy đếm số lượng các cây nhị phân tìm kiếm khác nhau thoả mãn các điều kiện sau:

- Cây gồm N nút.
- Giá trị các nút là các số nguyên dương không vượt quá M (N ≤ M).
- Giá trị các nút là phân biệt.
- Độ cao của cây không nhỏ hơn H (H ≤ N).
 
### Input

Dòng đầu tiên gồm 1 số nguyên T là số lượng bộ test.

T dòng tiếp theo, mỗi dòng gồm 3 số nguyên N, M, H (1 ≤ H ≤ N ≤ 80, N ≤ M ≤ 160).

### Output

Với mỗi bộ test, in ra kết quả là số cây nhị phân tìm kiếm thoả mãn điều kiện, tinh theo modulo 1012 + 9.

### Ví dụ

 | **Input** | **Output** |
|---|---|
| 2  2 3 2  3 3 2 | 6  5 |

**Giải thích**

Các trường hợp thoả mãn của test thứ 2:

![](data:image/jpeg;base64,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)

### CP04041 - SỐ T

Cho một dãy số T gồm N phần tử T1, T2, … , TN phân biệt. Một số nguyên dương được gọi là số T nếu tổng các chữ số của nó chia hết cho một trong N số Ti. Hãy đếm số lượng các số T phân biệt trong đoạn \[L, R\].

**Input**

Dòng đầu tiên gồm một số nguyên dương Q (1 ≤ Q ≤ 20) là số lượng truy vấn.

Mỗi truy vấn có dạng như sau:

Dòng đầu tiên gồm 2 số nguyên L, R (1 ≤ L ≤ R ≤ 1018).

Dòng thứ hai gồm 1 số nguyên N (1 ≤ N ≤ 10).

Dòng thứ 3 gồm N số nguyên T1, T2, … , TN (1 ≤ Ti ≤ 50). Các giá trị của Ti phân biệt.

**Output**

Với mỗi truy vấn, in ra kết quả trên một dòng là số lượng các số T phân biệt trong đoạn \[L, R\].

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  1 20  1  2  1 21  2  2 3  15 | 10  15 |

**Giải thích:** Ở truy vấn đầu tiên, các số thoả mãn là 2, 4, 6, 8, 11, 13, 15, 17, 19, 20.

### CP04043 - XẾP HÌNH

Có N loại hình hộp chữ nhật và M loại hình trụ tròn, loại hình hộp chữ nhật thứ *i* có kích thước x\[i\], y\[i\], z\[i\], loại hình trụ tròn thứ *j* có bán kính đáy là r\[j\] và chiều cao là h\[j\]. Tiến hành xếp chồng các hình hộp chữ nhật và hình trụ theo nguyên tắc:

\- Các hình hộp chữ nhật được đặt sao cho các cạnh song song với hệ trục tọa độ.

\- Mỗi hình đặt lên tạo thành một lớp. Mỗi lớp chỉ có đúng một hình;

\- Hình nằm trên đặt trọn vẹn trong mặt trên hình nằm dưới.

**Nhiệm vụ của bạn là hãy tìm** cách xếp để nhận được chồng các hình cao nhất.

**Input**

- Số đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test bắt đầu bằng 2 số nguyên N và M.
- N dòng tiếp theo, mỗi dòng gồm 3 số nguyên x\[i\], y\[i\], z\[i\] mô tả một hình chữ nhật.
- M dòng tiếp theo, mỗi dòng gồm 2 số nguyên r\[j\], h\[j\] mô tả một hình trụ.
- 0 &lt; x\[i\], y\[i\], z\[i\], r\[j\], h\[j\] ≤ 10^9.
 
**Output**

- Với mỗi test, hãy in độ cao của vật thể cao nhất có thể thu được.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  1 0  10 20 30 | 40 |

**Giải thích test 1:** Chọn hình chữ nhật có đáy 20x30, chiều cao 10 và hình chữ nhật đáy 10x20, chiều cao 30. Tổng chiều cao của hình tháp được tạo ra bằng 40.

Sử dụng hình chữ nhật có đáy 20x30 và 10x30 không hợp lệ, vì mép của khối hợp trên trùng với mép của khối hợp dưới.

**Subtask 1:** 50% số test đầu tiên: N = 0, M ≤ 100.

**Subtask 2:** 50% số test còn lại: N, M ≤ 100.

### CP04046 - DFS

used\[1 ... n\] = 0, ..., 0;

procedure dfs(v):

print v;

used\[v\] = 1;

for i = 1, 2, ..., n:

if (a\[v\]\[i\] == 1 and used\[i\] == 0):

dfs(i);

dfs(1);

Đoạn giả mã Pascal trên rất quen thuộc với những ai đã từng học về kỹ thuật duyệt DFS.

Bài toán đặt ra cho bạn hôm nay như sau: Cho trước kết quả duyệt DFS trên một cây T có N đỉnh (đánh số các node từ 1 đến N). Hãy đếm xem có thể co bao nhiêu cây khác nhau cho kết quả duyệt DFS như vậy.

**Input**

Dòng đầu ghi số N

Dòng thứ 2 có N số nguyên, là một hoán vị của các số từ 1 đến N. Số 1 luôn ở vị trí đầu tiên.

**Ouput**

Ghi số số cây T có N đỉnh cho kết quả duyệt DFS như vậy. Kết quả tính theo modulo 109 + 7

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  1 2 3 | 2 |

Giải thích ví dụ: Có hai cây thỏa mãn là (1,2); (1,3) và (1,2); (2,3)

**Ràng buộc:**

- Có 40% test ứng với 1 ≤ N ≤ 13
- Có 60% test ứng với 13&lt;N≤100

### LATXU - LATXU

lật xu

### OLP018 - LÁT CẮT

Cho một dãy bit nhị phân gồm có N bit: b\[0\] b\[1\] … b\[N-1\]. Bạn được phép thực hiện K lát cắt.

Có tổng cộng N+1 vị trí có thể cắt: | b\[0\] | b\[1\] | … | b\[N-1\] |.

Xét các dãy bit con kẹp giữa hai lát cắt, hai phần thừa bên ngoài bỏ không tính, như vậy với K lát cắt sẽ tạo ra được K-1 dãy con. Một cách cắt được gọi là đẹp nếu như tập hợp các số này biểu diễn dưới cơ số 10 tạo thành một tập hợp đầy đủ từ 1 à M với M nào đó.

Ví dụ với dãy bit 101101001110 và cách cắt 10 | 11 | 010 | 01 | 1 | 10 là đẹp, vì dãy con thu được là 11, 010, 01, 1 tương ứng với 3, 2, 1, 1 trong cơ số 10.

Kí hiệu f(K) là số cách cắt đẹp với K lát cắt. Bạn hãy tính giá trị biểu thức S sau theo modulo 1000000007:

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGYAAABLCAYAAACC7fKKAAAFe0lEQVR4Ae1b27HjIAx1XRREPVTD13ZCMeyIt7EAEdsbZVa5cyc2BiHOQUgI5/DyYYnAwVIrUcoLMUwngRAjxDBFgKlaYjFCDFMEmKolFiPEMEWAqVpiMUIMUwSYqiUWI8QwRYCpWmIxQgxTBJiqxcxirNfH4Q9tK1zOeAVlh/LG1eL+yhnlj+Pwalapb8T4nhkxgJT1Wp1JcMZ425LijDcNdwVfq4WYAsbTFwC6PgNsexaEmKdRJ8iz1sOfVtpHo7De9MuTEEMA8uEq1loPqxb4jOBqnE3LmPNGga/p/pUJ9YMaspQ9zEYR57zNzgScvrY++JfyPF2IxfSIvHzvjLfFqYOFKK96/wIqCDEvE9GIz+Hu0S1NbeRcqiPElPZ9uF0a/dYFw3D5twB8S1sh5i1kb8oVYm4C+FZzIeYtZG/K5UOM1dc9Sr9nWd6fUzk3sflqcz7EpE1l3UDmnT8FH+ethiSmEENB66M6p7C3DZ2X0uK+p8/ezJtlQhfZa2e81k2GYS4UeepC/i/vnZEKl6K1xTjrTZiNKRWitDehB+s1usm49LFdYHWTdtkhx+qYxiH1CPk4OCaAFFBM92BHBg7SPJC3a7PbF+uO+hY4ylFFHofy5o/xSkGaqRM00HVBTDwficonCQ7Yj2cfRZGB8M+LYSbnQXXnMzOhyMZzVD3IXw0A/F5JpiKSEgFXQpMllkmc20Y8V91C7SkxYVlBZ+wny0ZWjvodZ3H2OZA3e+oDVrD2RwQQETnOmnCeNLSM0GbtP9fEDByqNXfWXCrEHTl7DgTp5CwPSB/xPZ6UVey5TraS7lCvVk9XUYerlZ0rTokJp4khRKWvjWfxT9yl4+YUKq8GROlxvYwlAkeshU6aOhAcgP8gTpzQP7oSVe0XxEDF6CRhdoU0fG2LXp18w2jfMR0wIrZzprvNzxIJMzb1N+0n66TA3+rp+wjn/uNZ02opJRADYpuwcsF0r8Rj9xkIIPuWDlTfMV7mAiLh5Q/lVTq827Lk4Gfm8nFiwDQRsyx7jOlUeoyKi6DY/81NJOKwLx0RgKvLUVrSdt7QIcjHiRke0SYlJjP2laUsIEeY6ReErwWR3EVUtAQu+b0yQTfJWcofhMvnaKMdXFJoQkxb+8lrSLlsLReDzsPEKYAOKqVlc9gfCmzdew3bpe4olo9aTJ71Z2efO765lAywmBXDQJ7Zx1CtLlkASmC2DgQHWGlK9BhfKsHGVZdB7GksQ4iBFAxs5pyP6Yi6A8dSE2PRDz0Js3Ox9FC7CpaAAIq0x1aNONMrHiFSTb4Ye4bvkyKxK6tCiEG0/FbRBpAkFYFk1Aqw1lTrwtpOyogTjTExHwLjICWJf8BPIcEmXhlKiSCOBfRP6GNiSgzN3Pthw70z7WYPgIhkwLKMbQEwGW0ZLa/Wthhcu/hO9jCH1jVjSQwpcuoGEm+BiNYfVUf9CSmlCwD1gfOYHWtlRwzmdAtAwwsIVCBfdTcrMOzgnz/gRUxY089RD0Q2W/9k5/7Psd7qkBEx0TFukYCQtgpDt9D5YmVGxHwRBYZdCzEMSQGV2BET00FtZDVHLqePVucbcyn8nrIjJh7MEY+tm7diPovm+BGSNeJHzFbaJA8Dvvs9TPvs967ZEQMzX9saoSnzZ/0Tv4D7e++5fYNWZsTATl15Y+Hn4qOMFw4T+pNAvOpPlPIiJmWT4Y2Tuh/JaZVuo9ke1g1PXH+CA1RJXsRk/5K+Se+u5TYwvI03MVE0GBWyIgZC35hRAR+zTtFfD6foYTYjDlBVWBGDavifFgoxTIkXYoQYpggwVUssRohhigBTtcRihBimCDBVSyxGiGGKAFO1xGKEGKYIMFVLLEaIYYoAU7XEYoQYpggwVesv3Vb4hF41ea0AAAAASUVORK5CYII=)

**Input:**

Dòng đầu tiên là số nguyên N (1 &lt;= N &lt;= 75).

Dòng tiếp theo gồm dãy bit b có N kí tự.

**Output:**

In ra một số nguyên là đáp án của bài toán.

**Test ví dụ:**

 | Test 1 | Test 2 |
|---|---|
| Input:  4  1011  Output:  10 | Input:  2  10  Output:  1 |

Giải thích test 1:

K = 2: | 1 | 011 , 1 | 01 | 1, 10 | 1 | 1, 101 | 1 |.

K = 3: | 1 | 01 | 1, | 10 | 1 | 1, 10 | 1 | 1 |, 1 | 01 | 1 |.

K = 4: | 10 | 1 | 1 |, | 1 | 01 | 1 |.

### OLP041 - TAM GIÁC VUÔNG CÂN

Cho vùng tọa độ Oxy bị giới hạn bởi gốc tọa độ (0, 0) và điểm trên cùng bên phải (X, Y). Nhiệm vụ của bạn là hãy xác định xem có bao nhiêu tam giác vuông cân.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 100).

Mỗi test gồm hai số nguyên X và Y.

**Giới hạn:**

Subtask 1 (25%) 0 &lt;= X, Y &lt;= 20.

Subtask 2 (25%) 0 &lt;= X, Y &lt;= 100.

Subtask 3 (50%) 0 &lt;= X, Y &lt;= 1000.

**Output:**

Với mỗi test, in ra số tam giác vuông tìm được trên một dòng.

**Example:**

 | Input | Output |
|---|---|
| 3  0 5  1 2  1 1 | 0  10  4 |

### OLP057 - PHÂN NHÓM BÀI TẬP LỚN

Thầy X tại trường P có K bài tập lớn. Lớp có N sinh viên. Mỗi sinh viên chỉ tham gia một nhóm duy nhất và K bài tập lớn cần phải giao đủ cho K nhóm sinh viên.

Tuy nhiên, trong lớp không phải sinh viên nào cũng hợp tác được với nhau. Giữa họ tồn tại một số mâu thuẫn nhất định, được đánh giá bằng chỉ số A\[i\]\[j\] (đại diện cho sinh viên i và sinh viên j). Chỉ số mâu thuẫn của một nhóm bằng tổng chỉ số mâu thuẫn giữa từng cặp thành viên.

Các bạn hãy giúp thầy X phân nhóm bài tập lớn sao cho tổng chỉ số mâu thuẫn của K nhóm là nhỏ nhất. Khi đó, cả thầy giáo và các bạn sinh viên đều cảm thấy hài lòng.

**Input**

- Dòng đầu chứa số nguyên dương N và K.
- N dòng tiếp theo, mỗi dòng gồm N số nguyên A\[\]\[\] (0 ≤ A\[i\]\[j\] ≤ 9).
- Input đảm bảo A\[i\]\[j\] = A\[j\]\[i\] và A\[i\]\[i\] = 0.
 
**Giới hạn:**

Subtask 1 (40%): N ≤ 500, K ≤ 100;

Subtask 2 (60%): N ≤ 2000, K ≤ min(N, 1000).

**Output**

- Hãy in ra đáp án là tổng chỉ số mâu thuẫn nhỏ nhất của K nhóm.
 
 

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5 2  0 0 1 1 1  0 0 1 1 1  1 1 0 0 0  1 1 0 0 0  1 1 0 0 0 | 0 |
| 3 2  0 2 0  2 0 1  0 1 0 | 1 |
| 6 2  0 1 1 1 1 1  1 0 1 1 1 1  1 1 0 1 1 1  1 1 1 0 1 1  1 1 1 1 0 1  1 1 1 1 1 0 | 6 |

Giải thích test 2: Nhóm (1) và (2, 3)

### OLP075 - THI ĐẤU

Team A có N thí sinh, mỗi thí sinh có sức mạnh bằng a\[i\], team B có M thí sinh, mỗi thí sinh có sức mạnh bằng b\[i\].

Luật thi đấu đối kháng như sau: Mỗi team chọn ra K thí sinh, thí sinh mạnh nhất được chọn của nhóm A sẽ thi đấu với thí sinh mạnh nhất của nhóm B, thí sinh mạnh thứ 2 của nhóm A sẽ thi đấu với thí sinh mạnh thứ 2 trong nhóm B... Trong một cuộc đấu đối kháng, thí sinh nào có sức mạnh lớn hơn sẽ chiến thắng.

Ban tổ chức là người nhà của team A, vì vậy đã cố ý lựa chọn K thí sinh nhóm A và K thí sinh nhóm B sao cho trong K cuộc đấu, thành viên đến từ team A luôn chiến thắng.

Nhiệm vụ của bạn là hãy tính xem BTC có bao nhiêu cách chọn các thí sinh để đạt được mục tiêu của mình?

**Input:**

Dòng đầu tiên chứa 3 số nguyên N, M, K (1 &lt;= K &lt;= 10).

Dòng tiếp theo gồm N số nguyên a\[i\].

Dòng cuối gồm M số nguyên b\[i\] (1 &lt;= a\[i\], b\[i\] &lt;= 10^9).

**Giới hạn:**

Subtask 1 (50%): 1 &lt;= N, M &lt;= 200

Subtask 2 (50%): 1 &lt;= N, M &lt;= 1000.

**Output:**

In ra đáp án tìm được theo modulo 10^9+9.

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 5 10 3  1 2 2 6 7  1 3 6 8 8 9 14 17 18 19 | 2 |

Giải thích test: (2, 6, 7) vs (1, 3, 6). Hai tổ hợp (2, 6, 7) tương ứng với 2 cách.

### OLP095 - BẢNG SỐ TƯƠNG ĐỒNG

Hai bảng số A và B được gọi là tương đồng bậc k nếu như:

1. Hai bảng có cùng kích thước
2. Hai phần tử tương ứng chênh lệch không quá k đơn vị |A\[i,j\] – B\[i,j\]| &lt;= k).
 
Cho số nguyên k và 2 bảng số X, Y có cùng kích thước m x n. Hãy tìm bảng số C và D tương ứng là bảng số con của X và Y sao cho C và D tương đồng và có kích thước lớn nhất (r, c là số hàng, cột của C, D, cần tìm r x c lớn nhất có thể).

**Input:**

Dòng đầu tiên chứa 3 số nguyên m, n, k.

m dòng tiếp theo, mỗi dòng gồm n số nguyên không âm mô tả bảng số X.

m dòng tiếp theo, mỗi dòng gồm n số nguyên không âm mô tả bảng số Y.

Các phần tử có giá trị không vượt quá 10^9.

**Output:**

In ra giá trị tích r x c lớn nhất tìm được.

**Giới hạn:**

Subtask 1: m, n &lt;= 16, k &lt;= 10^9

Subtask 2: m, n &lt;= 64, k = 0

Subtask 3: m, n &lt;= 64, k &lt;= 10^9

 

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 3 3 0  **1 1** 1  **1 1** 1  1 1 2  2 2 2  2 **1 1**  2 **1 1** | 4 |
| 3 3 1  1 1 1  1 1 1  1 1 1  2 2 2  2 1 1  2 1 1 | 9 |

### OLP096 - MÃ HÓA

Cho phép mã hóa X = X + X mod 100. Với hai số nguyên N và K, hãy thực hiện phép mã hóa K lần với số X ban đầu được khởi tạo bằng N.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 500).

Mỗi test gồm hai số nguyên N và K (1 &lt;= N, K &lt;= 10^9).

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 2  212 2  1003 3 | 248  1024 |

Giải thích test 1:

212 + 12 = 224, 224 + 24 = 248

### OLP130 - SỐ LƯỢNG DÃY NGOẶC ĐÚNG BT1

Biểu thức ngoặc là xâu chỉ gồm các ký tự ‘(’ hoặc ‘)’. Biểu thức ngoặc đúng và bậc của biểu thức ngoặc được định nghĩa một cách đệ qui như sau:

- Biểu thức rỗng là biểu thức ngoặc đúng và có bậc bằng 0,
- Nếu A là biểu thức ngoặc đúng có bậc bằng k thì (A) cũng là một biểu thức ngoặc đúng có bậc bằng k+1,
- Nếu A và B là hai biểu thức ngoặc đúng và có bậc tương ứng là k\_1 và k\_2 thì AB cũng là một biểu thức ngoặc đúng có bậc bằng max(k\_1,k\_2).
 
Ví dụ, ‘()(())’ là một biểu thức ngoặc đúng có bậc bằng 2 còn ‘(()(()))’ là một biểu thức ngoặc đúng và có bậc bằng 3.

**Yêu cầu:** Cho *n*, đếm số biểu thức ngoặc đúng có độ dài *n*.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 10)

Gồm nhiều dòng, mỗi dòng là một bộ dữ liệu, chứa một số nguyên *n (n &lt;= 100);*

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

Nếu kết quá có hơn 10 chữ số thì ghi theo định dạng: 5 chữ số đầu tiên, tiếp theo là 3 dấu chấm, cuối cùng là 5 chữ số cuối.

**Test ví dụ:**

 | Input | Output |
|---|---|
| 4  2  4  6  56 | 1  2  5  26374...50360 |

### S01 - LÀM TRÒN SỐ

Cho số nguyên dương không quá 9 chữ số. Hãy làm tròn số N theo quy tắc sau:

- Nếu N&gt;10, làm tròn đến số hàng chục gần nhất
- Sau đó nếu kết quả lớn hơn 100 thì làm tròn đến số hàng trăm gần nhất
- Sau đó nếu kết quả lớn hơn 1000 thì làm trong đến số hàng nghìn gần nhất
- Cứ tiếp tục như vậy …
 
Chú ý: Giá trị 5 sẽ được làm tròn lên.

**Input**

Dòng đầu ghi số bộ test (không quá 100)

Mỗi bộ test ghi số N trên một dòng (N nguyên dương và không quá 9 chữ số)

**Output**

Với mỗi test, ghi ra kết quả làm tròn tương ứng trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 7  15  14  5  99  12345678  44444445  1445 | 20  10  5  100  10000000  50000000  2000 |

### S02 - BỘI SỐ CHUNG NHỎ NHẤT

Viết chương trình tính bội số chung nhỏ nhất của hai số nguyên dương lớn (có thể đến 500 chữ số)

**Input:**  
 Dòng 1 ghi số bộ test. Mỗi bộ test gồm 2 dòng, mỗi dòng ghi một số.

**Output:**  
 Với mỗi bộ test ghi ra kết quả trên một dòng.

  
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3    12    100    1212    8888    121212121212121212    45678978 | 300    26664    102534181818181818079284 |

### S03 - LỰA CHỌN THAM LAM

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

### S05 - DÃY CON CÓ TỔNG NGUYÊN TỐ

Cho dãy số A\[\] có N phần tử là các số nguyên dương khác nhau từng đôi một. Hãy sắp xếp dãy theo thứ tự giảm dần, sau đó liệt kê tất cả các dãy con của A\[\] có tổng các phần tử là số nguyên tố.

**Input**

Dòng đầu ghi số bộ test, mỗi test có 2 dòng:

- Dòng đầu ghi số N (2 &lt; N &lt;15)
- Dòng thứ 2 ghi N số của dãy A\[\], các số đều nguyên dương, nhỏ hơn 100 và khác nhau từng đôi một.
 
**Output**

Với mỗi test, liệt kê tất cả các dãy con có tổng các phần tử là số nguyên tố theo, mỗi dãy con trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  4  3 2 5 4 | 2  3  3 2  4 3  5  5 2  5 4 2 |

### S06 - DÃY CON CÓ K PHẦN TỬ TĂNG DẦN

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

### S07 - HOÁN VỊ DÃY SỐ

Cho dãy số A\[\] có N phần tử là các số nguyên dương khác nhau từng đôi một. Hãy liệt kê tất cả các hoán vị của dãy số A\[\] theo thứ tự tăng dần, tức là hoán vị đầu tiên có giá trị tăng dần từ trái qua phải, hoán vị cuối cùng giảm dần từ trái qua phải.

**Input**

Dòng đầu ghi số N (1 &lt; N &lt; 9)

Dòng thứ 2 ghi N số của dãy A\[\] (0 &lt; A\[i\] &lt; 10000)

**Output**

Ghi mỗi hoán vị của dãy số trên một dòng

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  88 77 99 | 77 88 99  77 99 88  88 77 99  88 99 77  99 77 88  99 88 77 |

### S08 - TRỤC TỌA ĐỘ

Trên trục Ox tính từ vị trí 0, người ta muốn xếp nhiều nhất các đoạn thẳng sao cho không đoạn nào chồng lấn lên nhau. Đoạn thẳng thứ i có vị trí bắt đầu là X1\[i\] và kết thúc tại X2\[i\], với X1\[i\] &lt;= X2\[i\].

Hãy tính số đoạn thẳng nhiều nhất có thể được lựa chọn để đưa lên trục Ox và không có đoạn nào chồng lấn lên nhau.

**Input**

Dòng đầu tiên ghi số bộ test, không quá 10.

Với mỗi bộ test: dòng đầu ghi số N là số đoạn thẳng (không quá 105)

Tiếp theo là N dòng, mỗi dòng có 2 số nguyên mô tả đoạn thẳng. Các giá trị tọa độ đều là các số nguyên không âm và không quá 106.

**Output**

Với mỗi test, viết trên 1 dòng số lượng đoạn thẳng nhiều nhất có thể được lựa chọn thỏa mãn điều kiện đề bài.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  10  39 55  37 74  0 1  19 25  65 76  51 52  19 21  5 94  46 65  32 40 | 5 |

### S09 - NHIỀU NHẤT – ÍT NHẤT

Giả sử tra có N cuốn sách. Cuốn sách thứ i có Pi trang sách. Nhiệm vụ của bạn là giao sách đọc đến M sinh viên. Các ràng buộc:

- Mỗi cuốn sách được giao cho duy nhất một sinh viên.
- Mỗi sinh viên đọc ít nhất một cuốn sách.
- Các cuốn sách được giao cho một sinh viên liên tiếp nhau.
 
Nhiệm vụ của bạn là tìm giải pháp giao sách đọc cho sinh viên sao cho số lượng trang sách nhiều nhất giao cho một sinh viên là ít nhất. Ví dụ với số sách N là 4, số sinh viên M = 2 và số trang trong mỗi cuốn sách là {12, 34, 67, 90} ta có các cách phân công 2 sinh viên đọc sách như sau:

- \[12\] \[34, 67, 90\]: sinh viên 2 đọc nhiều nhất 34+67+90=191.
- \[12, 34\] \[67,90\]: sinh viên 2 đọc nhiều nhất 67+90 = 157.
- \[12, 34, 67\] \[90\]: sinh viên 1 đọc nhiều nhất 12+34+67 = 113
 
Như vậy, phương án 3 là 113 giao nhiều trang sách nhất cho một sinh viên là ít nhất.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào số lượng sách N và số lượng sinh viên M; dòng tiếp theo đưa vào số trang của mỗi sách; các số được viết cách nhau một vài khoảng trống.
- T, N, M, P\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N, M≤106; 1≤P\[i\]≤106.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng. Đưa ra -1 nếu không có giải pháp giao sách cho M sinh viên.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    4 2    12 34 67 90    3 2  15 17 20 | 113    32 |

### S109 - ĐỔI CHỖ ÍT NHẤT

Cho mảng A\[\] gồm n phần tử. Hãy tìm số phép đổi chỗ ít nhất giữa các phần tử của mảng để mảng A\[\] được sắp xếp. Ví dụ với A\[\] = {4, 3, 2, 1} ta cần thực hiện ít nhất 2 phép đổi chỗ: Swap(A\[0\], A\[3\]), Swap(A\[1\], A\[2\]).

 **Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên là số phần tử của mảng n và X; dòng tiếp theo là n số A \[i\] của mảng A \[\];các số được viết cách nhau một vài khoảng trống.
- T, n thỏa mãn ràng buộc: 1≤ T ≤100; 1≤ n ≤103.
 
 **Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 2    4    4 3 2 1    5    1 5 4 3 2 | 2    2 |

### S11 - TÁCH NHÓM TỐI ƯU

Cho dãy số A\[\] có N phần tử là các số nguyên dương. Với mỗi số nguyên K, hãy tính xem có thể tách dãy số A thành ít nhất bao nhiêu nhóm sao cho mỗi số trong nhóm đều có thể tìm được ít nhất một số khác **cùng nhóm** có chênh lệch **không vượt quá K.**

Ví dụ: A\[\] = {2, 6, 1, 7, 3, 4, 9}; K = 1 thì kết quả là 3 ứng với 3 nhóm {2,1,3,4}; {6,7}; {9}

**Input**

Dòng đầu ghi hai số N và K (0 &lt;= K &lt;= 105; 0 &lt;= N &lt;= 106).

Dòng thứ 2 ghi ra N số của dãy A\[\], các số nguyên dương và không quá 106.

**Output**

Ghi ra số nhóm ít nhất có thể.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 7 1  2 6 1 7 3 4 9 | 3 |

### S110 - SẮP XẾP LẠI DÃY CON

Cho mảng A\[\] gồm n phần tử. Hãy tìm dãy con liên tục của mảng A\[R\], .., A\[L\] sao cho khi sắp xếp lại dãy con ta nhận được một mảng được sắp xếp. Ví dụ với A\[\] = {10, 12, 20, 30, 25, 40, 32, 31, 35, 50, 60} ta chỉ cần sắp xếp lại dãy con từ A\[4\],.., A\[9\]: {30, 25, 40, 32, 31, 35} để có mảng được sắp.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào n là số phần tử của mảng A\[\]; dòng tiếp theo là n số A \[i\] của mảng A \[\]các số được viết cách nhau một vài khoảng trống.
- T, n, A\[i\] thỏa mãn ràng buộc: 1≤ T ≤100; 1≤ n ≤106; 0≤ A\[i\] ≤107.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 2    11    10 12 20 30 25 40 32 31 35 50 60    9    0 1 15 25 6 7 30 40 50 | 4 9    3 6 |

### S12 - SỐ XA CÁCH

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

### S121 - BẦU CỬ

Khu dân cư ABC tiến hành bầu tổ trưởng dân phố. Có M ứng viên và N cử tri. Người dân trong khu dân cư đã chán ngấy với việc các ứng viên vận động tranh cử, câu kéo phiếu bầu trong các nhiệm kỳ trước nên họ quyết định đặt ra quy định mới như sau:

- Các ứng viên được đánh số từ 1 tới M. Mỗi cử tri sẽ viết ra đúng 1 số thứ tự ứng viên mình muốn chọn và bỏ vào hòm phiếu.
- Người trúng cử là người có số phiếu bầu **nhiều thứ hai**
- Nếu không có người đứng thứ hai thì kết quả bầu cử sẽ bị hủy bỏ
- Nếu có nhiều hơn 1 người cùng có số phiếu nhiều thứ hai thì người nào có số thứ tự nhỏ nhất sẽ được chọn.
 
Viết chương trình xác định người trúng cử.

**Input**

Dòng đầu ghi hai số N và M (1 &lt; M &lt; 10, 5 &lt; N &lt; 500).

Dòng thứ 2 ghi N giá trị trong các phiếu bầu. Các giá trị đảm bảo hợp lệ (tức là từ 1 đến M).

**Output**

Ghi ra số thứ tự của người trúng cử.

Hoặc nếu không có ai trúng cử thì ghi ra NONE

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 10 4  2 3 1 2 3 4 1 2 3 2 | 3 |
| 8 4  1 2 3 4 4 3 2 1 | NONE |

### S122 - HỢP VÀ GIAO CỦA HAI TẬP HỢP TỪ

Trong lập trình cơ bản, một từ được hiểu là một dãy ký tự liên tiếp không chứa khoảng trống, dấu tab hoặc dấu xuống dòng.

  
 Hãy xác định tập hợp các từ khác nhau trong một xâu ký tự, sau khi đã chuyển hết về dạng chữ thường. Sau đó nhập hai dòng ký tự và hiển thị hợp và giao của hai tập từ tương ứng.

**Input**

Chỉ có 2 dòng, mỗi dòng có độ dài không quá 1000 ký tự.

**Output**

Dòng 1 ghi hợp của 2 tập từ theo thứ tự từ điển

Dòng 2 ghi giao của 2 tập từ theo thứ tự từ điển.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| Lap trinh huong doi tuong  Ngon ngu lap trinh C++ | c++ doi huong lap ngon ngu trinh tuong  lap trinh |

### S123 - DI CHUYỂN ROBOT

Một robot xuất phát từ vị trí (0,0) mặt quay về hướng Bắc. Mỗi lần chỉ có một trong 4 lệnh chuyển động là G, L, R, B tương ứng là tiến về phía trước, tiến sang trái, tiến sang phải, lùi về phía sau một đơn vị.

Cho dãy lệnh chuyển động. Hãy tính xem vị trí cuối cùng của robot là vị trí nào?

**Input**

- Dòng đầu tiên ghi n (n≤100) là số lệnh robot cần thực hiện.
- Dòng thứ hai là dãy n ký tự mô tả dãy lệnh robot thực hiện
 
**Output**

Ghi ra hai số nguyên là tọa độ (x,y) của vị trí cuối cùng robot

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  GLLRB | -1 0 |
| **Input** | **Output** |
| 2  RG | 2 0 |

### S124 - SẮP XẾP ĐOẠN CON

Cho dãy số nguyên A có N phần tử. Hãy đếm số lượng chỉ số M &lt; N thỏa mãn: nếu sắp xếp đoạn con (A1,…,AM) và (AM+1, …, AN) theo thứ tự tăng dần thì ta được dãy số A tăng dần.

**Input**

Dòng đầu ghi số bộ test T

Mỗi bộ test gồm 2 dòng:

- Dòng đầu ghi số N (2 ≤ N ≤ 105)
- Dòng thứ hai: ghi N số của dãy A (|Ai| ≤ 109).
 
**Output**

Với mỗi bộ test:

- Dòng đầu ghi ra số K là số lượng chỉ số M tìm được
- Dòng thứ 2 ghi ra K giá trị chỉ số thỏa mãn theo thứ tự tăng dần. Nếu K = 0 thì dòng này bỏ trống.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  2  2 1  5  2 1 3 5 4 | 0  2  2 3 |

### S125 - ĐẾM ƯỚC SỐ

Cho hai số nguyên dương n và k. Hãy đếm số ước số khác nhau của tổ hợp chập k của n phần tử.

**Input:**

Dữ liệu vào gồm nhiều dòng, mỗi dòng ghi hai số nguyên dương n và k (0 ≤ k ≤ n ≤ 431). (chú ý: không có dòng ghi số bộ test, cần tự đọc đến hết các dòng của luồng vào).

**Output:**

Ghi ra kết quả trên một dòng. Dữ liệu vào đảm bảo kết quả không vượt quá 263 – 1.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 5 1  6 3  10 4 | 2  6  16 |

### S127 - XÂU CON LỚN NHẤT

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

### S129 - PHÉP TOÁN OR

Phép toán trên thao tác bit OR lấy 2 dãy bit có độ dài bằng nhau và thực hiện phép toán lý luận bao hàm OR trên mỗi cặp bit tương ứng. Kết quả ở mỗi vị trí sẽ là 0 nếu cả 2 bit là 0, ngược lại kết quả là 1. Trong C, C++, Java toán tử thao tác bit OR được biểu diễn bằng kí hiệu "|" (vạch đứng )

Ví dụ : 10|17 = 01010|10001=11011=27

Cho một mảng a gồm n phần tử. Một dãy con liên tiếp của a được định nghĩa là một dãy a\[l\], a\[l+\]),a\[l+2\],...,a\[r\] với 1 ≤ l ≤ r ≤ n

Ta định nghĩa phép toán OR của 1 dãy con liên tiếp của mảng a là việc thực hiện phép toán thao tác bit OR của toàn bộ các phần tử trong dãy con đó.

OR(l,r) = a\[l\] | a\[l+1\] | a\[l+2\]|...|a\[r\]

Nhiệm vụ của bạn là tính giá trị OR của toàn bộ các dãy con của một mảng a cho trước và đếm xem có bao nhiêu giá trị khác nhau.

**Input:**

Dòng thứ 1 gồm 1 số n (1 ≤ n ≤ 1e5): số phần tử của mảng a

Dòng thứ 2 gồm n số a\[1\], a\[2\], ..., a\[n\] ( 0 ≤ a\[i\] ≤ 1e9)

**Output:**

Với mỗi testcase, in ra kết quả trên 1 dòng.

**Ví dụ :**

 | Input | Output |
|---|---|
| 3  1 2 3 | 3 |

Giải thích test:

Ta có tất cả 6 dãy con: (các số trong ngoặc là vị trí đầu và cuối )

1. (1,1) -&gt; 1
2. (1,2) -&gt; 1|2 = 2
3. (1,3) -&gt; 1|2|3 = 3
4. (2,2) -&gt; 2
5. (2,3) -&gt; 2|3=3
6. (3,3) -&gt; 3
 
Có 3 giá trị khác nhau là 1, 2, 3-&gt; kết quả là 3.

### S131 - BIẾN ĐỔI A – B

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

### S133 - VỊ TRÍ CHẴN

Cho trước 1 chữ số d (0 ≤ d ≤ 9) , ta gọi họ số đặc biệt của d là tập các số tự nhiên mà chữ số d chỉ xuất hiện tại vị trí chẵn (không xuất hiện trong vị trí lẻ).

Ví dụ: Số 1717171 là 1 số trong họ số đặc biệt của chữ số 7

Số 20 là 1 số trong họ số đặc biệt của chữ số 2.

Bài toán đặt ra là: *Cho trước 1 chữ số d, hãy đếm số lượng các số thuộc họ số đặc biệt của d nằm trong đoạn từ \[a,b\] mà là bội số của 1 số m cho trước.*

**Input:**

Dòng đầu tiên gồm 2 số m và d (1 ≤ m ≤ 2000, 0 ≤ d ≤ 9)

Dòng thứ 2 gồm 2 số a và b ( a ≤ b, số chữ số của cả a và b bằng nhau, không vượt quá 2000 và không có chữ số 0 ở đầu).

**Output:**

In ra kết quả bài toán. Vì kết quả bài toán có thể rất lớn nên kết quả in ra phải được lấy dư theo 109 + 7

Ví dụ:

 | **Input** | **Output** |
|---|---|
| 43 3  587 850 | 1 |

Giải thích test:

Trong khoảng từ 587 đến 850 chỉ có duy nhất 1 số thuộc họ số đặc biệt của chữ số 3 mà là bội của 43 đó là 731 (số 3 xuất hiện tại vị trí số 2 là vị trí chẵn)

### S135 - BÀI TOÁN CHỮ SỐ - 2

Hãy tìm 3 chữ số đầu tiên trước dấu phẩy của số (3+sqrt(5))^n.

Ví dụ:

Với n = 5, (3+sqrt(5))^5 = 3935.73982… Đáp số là 935.

Với n = 2, (3+sqrt(5))^2 = 27.4164079… Đáp số là 027.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 100).

Mỗi test gồm một số nguyên n (n ≤ 2 000 000 000).

**Output:**

Với mỗi test in ra STT và đáp án tìm được. In ra đủ 3 chữ số như test ví dụ (n = 2, in ra 027).

**Ví dụ:**

 | Input | Output |
|---|---|
| 2  5  2 | Case #1: 935  Case #2: 027 |

### S14 - TRẢ LƯƠNG CHO LẬP TRÌNH VIÊN

Trong các công ty IT, lập trình viên là một loại nhân sự đặc biệt. Nếu trả mức lương quá thấp, anh ta sẽ không muốn làm việc, năng suất sẽ thấp, thậm chí thỉnh thoảng lại dọa bỏ đi nơi khác. Nếu trả mức lương quá cao thì anh ta lại lười biếng và chẳng muốn làm việc gì cả. Mức lương vừa đủ sẽ khiến động lực làm việc tăng cao và năng suất sẽ là cao nhất.

Giả sử có N lập trình viên, mỗi người có một ngưỡng trả lương từ A\[i\] đến B\[i\] gọi là vừa đủ. Nếu lương nhỏ hơn A\[i\] thì số dòng code đúng mỗi ngày của lập trình viên thứ i sẽ là X, nếu trong đoạn từ A\[i\] đến B\[i\] thì số dòng code sẽ là Y, còn nếu lớn hơn B\[i\] thì số dòng code sẽ là Z. Tất nhiên, Y&gt;X và Y&gt;Z.

Hãy giúp giám đốc công ty chọn ra mức lương nào đó chung cho cả N lập trình viên và tổng số dòng code đúng trong một ngày là lớn nhất có thể.

**Input**

Dòng 1 ghi 4 số N, X, Y, Z (1 &lt;= N &lt;=20000; 0 &lt;= X,Y,Z &lt;=1000)

N dòng tiếp theo, mỗi dòng ghi hai số A\[i\] và B\[i\] (0 &lt;= A\[i\] &lt;= B\[i\] &lt;= 109)

**Output**

Ghi ra số dòng code đúng tối đa có thể đạt được.

**Ví dụ**

 | **Input** | **Ouput** |
|---|---|
| 4 7 9 6  5 8  3 4  13 20  7 10 | 31 |

### S20 - XÂU NHỊ PHÂN XEN KẼ

Một xâu nhị phân được gọi là xen kẽ nếu giá trị 0 ở ngay bên cạnh giá trị 1 và không có hai giá trị nào bằng nhau ở cạnh nhau. Hãy viết chương trình liệt kê các xâu nhị phân xen kẽ có độ dài N.

**Input**

Chỉ có một dòng ghi số N (2 ≤ N ≤ 1000)

**Output**

Ghi ra các xâu nhị phân xen kẽ, mỗi xâu trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3 | 0 1 0  1 0 1 |

### S21 - GIÁ TRỊ LỚN NHẤT

Cho dãy số nguyên A\[\] có N phần tử.

- Gọi **f(i,j) = |ai| + |ai+1| + … + |aj|**
- Goij **g(i,j) = ai + ai+1 + … + aj**
 
Với tất cả các cặp 1 ≤ i ≤ j ≤ N.

Hãy tính **giá trị lớn nhất của f(i,j) + g(i,j).**

**Input**

Dòng đầu ghi số N (1 ≤ N ≤ 50000)

Dòng thứ 2 ghi N số nguyên của dãy A\[\]

**Output**

Ghi ra giá trị lớn nhất của f(i,j) + g(i,j)

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  -3 5 -10 8 -2 | 26 |

### S22 - KHOẢNG CÁCH NGẮN NHẤT

Trong mặt phẳng tọa độ, khoảng cách Manhattan giữa 2 điểm A, B được định nghĩa là

d(A,B) = |xA – xB| + |yA – yB|

Cho hai tập điểm S1 và S2 trong đó:

- S1 chứa tập điểm phân biệt nằm trên đường y = c1
- S2 chứa tập điểm phân biệt nằm trên đường y = c2
 
Hãy tính khoảng cách Manhattan ngắn nhất giữa hai điểm p Î S1 và q Î S2 và đếm xem có bao nhiêu cặp điểm phân biệt có khoảng cách bằng khoảng cách ngắn nhất.

**Input**

- Dòng đầu tiên ghi hai số N, M (1 ≤ N,M ≤ 5000000) trong đó N là số phần tử trong S1, M là số phần tử trong S2
- Dòng thứ 2 ghi hai số c1 và c2 (- 108 ≤ c1,c2 ≤ 108).
- Dòng thứ 3 ghi N số của tập S1 (các số có trị tuyệt đối không quá 108)
- Dòng thứ 4 ghi M số của tập S2 (các số có trị tuyệt đối không quá 108)
 
**Output**

Ghi ra trên một dòng hai số nguyên lần lượt là khoảng cách ngắn nhất và số cặp điểm có khoảng cách ngắn nhất.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3 4  1 -3  3 0 6  -2 5 4 2 | 5 3 |

### S23 - TÍNH TỔNG GIÁ TRỊ ĐẶC BIỆT

Cho một xâu S chỉ bao gồm các chữ số. Với mỗi một xâu con X liên tiếp của S có độ dài bằng K, giá trị đặc biệt của nó được tính bằng giá trị của X trong hệ cơ số B modulo M.

Nhiệm vụ của bạn là tính tổng giá trị đặc biệt của tất cả các xâu con của S có độ dài bằng K.

**Input:**

Dòng đầu tiên gồm xâu S có độ dài không quá 300 000 gồm các kí tự từ 0 – 9.

Dòng tiếp theo là số nguyên K, B và M (1 ≤ K ≤ |S|, 2 ≤ B ≤ 10, 1 ≤ M ≤ 1000).

**Output:** In ra đáp án tìm được.

**Ví dụ:**

 | **Test 1** | **Test 2** |
|---|---|
| Input:  12212  3 3 5  Output:  5 | Input:  111101  4 2 15  Output:  27 |

Giải thích test 1:

*Giá trị của xâu con 122 trong cơ số 3 bằng 17 % 5 = 2.*

*Giá trị của xâu con 221 trong cơ số 3 bằng 25 % 5 = 0.*

*Giá trị của xâu con 212 trong cơ số 3 bằng 23 % 5 = 3.*

*Tổng của chúng bằng 5.*

### S24 - TỔNG GẦN NHẤT

Cho dãy số A\[\] có N số nguyên dương và số M.

Hãy chọn ra 3 số trong dãy A\[\] sao cho tổng 3 số đó nhỏ hơn M nhưng gần với M nhất.

In ra tổng 3 số tìm được.

**Input**

- Dòng đầu ghi số bộ test (không quá 10)
- Mối test có hai dòng. Dòng đầu ghi 2 số N và M (1 ≤ N ≤ 100; 10 ≤ M ≤ 300000). Dòng thứ 2 ghi N số của dãy số A\[\]. Các số đều nguyên dương và không quá 6 chữ số.
- Input đảm bảo luôn có ít nhất một bộ ba số có tổng nhỏ hơn M.
 
**Output**

Mỗi test ghi giá trị tổng của 3 số tìm được trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  5 21  5 6 7 8 9  10 500  93 181 245 214 315 36 185 138 216 295 | 21  497 |

### S25 - CHÊNH LỆCH NHỎ NHẤT

Cho dãy A\[\] có N số nguyên, mỗi số có đúng K chữ số (có thể có chữ số 0 ở đầu). Gọi độ chênh lệch của dãy là hiệu giữa phần tử lớn nhất và bé nhất của dãy.

Bạn có thể hoán vị các chữ số của một số để tạo số mới (có thể có chữ số 0 ở đầu). Bằng cách hoán vị tất cả n số **theo cùng một cách**, ta nhận được dãy số mới.

Tìm độ chênh lệch nhỏ nhất có thể tạo được.

**Input:**

Dòng đầu chứa 2 số N và K. (1 ≤ N, K ≤ 8)

N dòng sau, mỗi dòng chứa 1 số nguyên có K chữ số.

**Output:**

Độ chênh lệch nhỏ nhất tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3 3  010  909  012 | 3 |

*Giải thích test ví dụ:*

*Đổi chỗ chữ số thứ 1 và 2 có thể nhận được dãy 100, 99, 102.*

### S26 - BIẾN ĐỔI VỀ 0

Cho số tự nhiên N và thực hiện trừ N lần lượt N đi chữ số đầu tiên của N để N trở về 0. Ví dụ với N=13 ta thực hiện các phép dịch chuyển N về 0 như sau:

- Bước 1: N=N-1 = 13-1=12
- Bước 2: N=N-1 = 12-1=11
- Bước 3: N=N-1 = 11-1=10
- Bước 4: N=N-1 = 10-1=9
- Bước 5: N=N-1 = 9-9=0
 
Cho K là số các phép dịch chuyển N về 0 theo nguyên tắc kể trên. Nhiệm vụ của bạn là tìm số N lớn nhất từ xuất phát điểm ban đầu.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là số tự nhiên K được viết trên một dòng.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤106.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    1    2 | 9  10 |

### S28 - MÃ SỐ

Số lượng máy tính ở các phòng thực hành nhà A3 tăng lên nhanh chóng. Để gán mã cho các máy tính của PTIT người ta sử dụng mã gồm 2\*N ký tự, trong đó:

- N ký tự đầu tiên là hoán vị của N chữ cái in hoa đầu tiên, tính từ A.
- N ký tự tiếp theo là các ký tự số bất kỳ từ 1 đến N (có thể trùng nhau).
 
Người ta ước tính chỉ cần N = 5 là đủ để gán mã cho toàn bộ máy tính kể cả khi mở rộng quy mô các phòng thực hành. Hãy viết chương trình liệt kê các mã tạo được với giá trị N cho trước.

**Input**

Chỉ có duy nhất số N (1 &lt; N &lt; 6)

**Output**

Ghi ra lần lượt các mã khác nhau tạo được theo thứ tự từ điển, mỗi mã ghi trên một dòng

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2 | AB11  AB12  AB21  AB22  BA11  BA12  BA21  BA22 |

### S30 - QUÂN VUA TRÊN BÀN CỜ

Trên bàn cờ vua kích thước 8\*8 thì quân vua được phép di chuyển đến cả 8 ô liền kề theo cả đường dọc và đường chéo. Tất nhiên quân vua sẽ không thể di chuyển được ra ngoài bàn cờ.

Cho 2 ô trên bàn cờ gọi là ô bắt đầu và ô kết thúc. Hãy tính xem quân vua cần ít nhất bao nhiêu bước để di chuyển từ ô bắt đầu đến ô kết thúc.

**Input**

Có 2 cặp số nguyên s1,s2 và f1,f2 lần lượt và vị trí ô bắt đầu và ô kết thúc. Các vị trí đảm bảo nằm trong phạm vi bàn cờ.

**Output**

Số bước đi ít nhất của quân vua

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4 3 1 6 | 3 |
| 5 5 5 6 | 1 |

 

Giới hạn thời gian: 1s

### S31 - DÃY CON CÓ TỔNG BẰNG S

Cho dãy số A\[\] có n phần tử và số nguyên dương S. Hãy tìm dãy con có ít phần tử nhất của A\[\] có tổng các phần tử đúng bằng S.

**Input**

Dòng đầu ghi hai số n và S. (n ≤ 30; S ≤ 109).

Dòng thứ 2 ghi n số của dãy A\[\], các số đều nguyên dương và không quá 9 chữ số.

**Output**

Ghi ra độ dài của dãy con ngắn nhất có tổng bằng S.

Nếu không có kết quả đúng thì ghi ra -1

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 10 390  200 10 20 20 50 50 50 50 100 100 | 5 |

### S32 - MÃ GRAY

Số nhị phân được xem là cách mặc định biểu diễn các số. Tuy nhiên, trong nhiều ứng dụng của điện tử và truyền thông lại dùng một biến thể của mã nhị phân đó là mã Gray. Mã Gray độ dài n có mã đầu tiên là n số 0, mã kế tiếp của nó là một xâu nhị phân độ dài n khác biệt với xâu trước đó một bít. Ví dụ với n=3 ta có 23 mã Gray như sau: 000, 001, 011, 010, 110, 111, 101, 100. Hãy viết chương trình liệt kê các mã Gray có độ dài n.

**Input:** Dòng đầu tiên là số lượng test T. T dòng kế tiếp ghi lại mỗi dòng một test. Mỗi test là một số tự nhiên n. T, n thỏa mãn ràng buộc: 1≤T, n≤10.

**Output:** Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 2  3  4 | 000 001 011 010 110 111 101 100  0000 0001 0011 0010 0110 0111 0101 0100 1100 1101 1111 1110 1010 1011 1001 1000 |

### S33 - LIỆT KÊ XÂU KÝ TỰ

Cho chữ cái c in hoa (‘A’ &lt; c &lt; ’K’) và số nguyên K (0 &lt; K &lt; (c – ‘A’)).

Hãy tìm cách liệt kê tất cả các xâu ký tự khác nhau được tạo ra bởi các chữ cái tính từ ‘A’ đến ký tự c. Các ký tự được phép lặp lại nhưng không tính các xâu là hoán vị của xâu nào đó đã liệt kê trước đó.

Xem ví dụ để hiểu thêm yêu cầu đề bài.

**Input**

Chỉ có một dòng ghi chữ cái c và số nguyên K thỏa mãn ràng buộc đề bài.

**Output**

Ghi ra lần lượt các xâu ký tự kết quả theo thứ tự từ điển, mỗi xâu trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| D 2 | AA  AB  AC  AD  BB  BC  BD  CC  CD  DD |

### S34 - TỔNG ƯỚC SỐ

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

### S40 - TÍNH LŨY THỪA

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

### S41 - NỐI DÂY 2

Cho N sợi dây với độ dài khác nhau được lưu trong mảng A\[\]. Nhiệm vụ của bạn là nối N sợi dây thành một sợi sao cho tổng chi phí nối dây là nhỏ nhất. Biết chi phí nối sợi dây thứ i và sợi dây thứ j là tổng độ dài hai sợi dây A\[i\] và A\[j\].

**Input**

Dòng đầu ghi số bộ test T (T&lt;10). Mỗi bộ test gồm 2 dòng. Dòng đầu tiên là số nguyên N (N ≤ 2\*106).

Dòng tiếp theo gồm N số nguyên dương c\[i\] ( 1 ≤ A\[i\] ≤ 109).

**Output**

In ra đáp án của bộ test trên từng dòng, theo modulo 109+7.

**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 7  2 4 1 2 10 2 3 | 59 |

### S42 - PHẦN TỬ LỚN NHẤT TRONG DÃY CON

Cho dãy số A\[\] gồm có N phần tử và số nguyên K.

Với mỗi dãy con liên tiếp có độ dài bằng K (từ trái sang phải), bạn hãy in ra phần tử lớn nhất trong dãy con này.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm số nguyên N và K (1≤ N ≤ 100 000, 1 ≤ K ≤ N).

Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 109).

**Output:**

Với mỗi test, in ra trên một dòng N-K+1 số nguyên là đáp án tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  9 3  1 2 3 1 4 5 2 3 6  10 4  8 5 10 7 9 4 15 12 90 13 | 3 3 4 5 5 5 6  10 10 10 15 15 90 90 |

### S43 - LỰA CHỌN TỐI ƯU

Bạn được giao cho N công việc, công việc thứ i có thời gian bắt đầu là A\[i\] và kết thúc tại B\[i\]. Tại một thời điểm, bạn chỉ có thể làm một công việc.

Bạn hãy lựa chọn các công việc một cách tối ưu sao cho số công việc làm được là nhiều nhất.

**Input:** Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm 1 số nguyên N ( 1 ≤ N ≤ 100 000).

N dòng tiếp theo, mỗi dòng gồm 2 số A\[i\] và B\[i\] (0 ≤ A\[i\] &lt; B\[i\] ≤ 106).

**Output:** Với mỗi test, in ra đáp án trên một dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  6  5 9  1 2  3 4  0 6  5 7  8 9 | 4 |

*Giải thích test: Lựa chọn công việc 2, 3, 5, 6.*

### S45 - LŨY THỪA MA TRẬN

Cho ma trận vuông A kích thước N x N. Nhiệm vụ của bạn là hãy tính ma trận X = AK với K là số nguyên cho trước. Sau đó, **tính tổng các phần tử của cột cuối cùng**. Đáp số có thể rất lớn, hãy in ra kết quả theo modulo 109+7.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 100).

Mỗi test bắt gồm một số nguyên N và K (1 ≤ N ≤ 10, 1 ≤ K ≤ 109) là kích thước của ma trận và số mũ.

**Output:**

Với mỗi test, in ra kết quả của ma trận X.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  2 5  1 1  1 0  3 1000000000  1 2 3  4 5 6  7 8 9 | 8  581039956 |

Giải thích:

A^5 = 8 5

 5 3

Tổng các phần tử trên cột cuối cùng bằng 5+3 = 8.

 597240088 35500972 473761863

B^1000000000 = 781257150 154135232 527013321

 965274212 272769492 580264779

Tổng các phần tử trên cột cuối cùng là:

(473761863+527013321+580264779) % 1000000007 = 581039956

### S46 - SẮP XẾP ĐƠN GIẢN

Cho một dãy số a\[\] có n phần tử gồm các số từ 1 đến n theo 1 thứ tự ngẫu nhiên. Nhiệm vụ của bạn là sắp xếp lại dãy số này theo thứ tự tăng dần với điều kiện : ở mỗi bước sắp xếp, bạn chỉ được chọn 1 số ở 1 vị trí bất kì và chuyển số đó lên đầu dãy hoặc về cuối dãy.

Hãy tính số bước tối thiểu cần thực hiện để hoàn thành việc sắp xếp.

**Input**

- Dòng đầu tiên ghi 1 số n: số lượng phần tử của dãy a (1 ≤ n ≤ 100000)
- Dòng tiếp theo gồm n số từ 1 đến n theo thứ tự ngẫu nhiên
 
**Output**

- Một số nguyên duy nhất là số bước tối thiểu cần thực hiện để hoàn thành việc sắp xếp.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  4 1 2 5 3 | 2 |

### S47 - TÌM DÃY SỐ

Cho dãy số nguyên A\[\] gồm có N phần tử. Nhiệm vụ của bạn là tìm dãy số B\[\] có tổng phần tử nhỏ nhất thỏa mãn tính chất A\[i\] **/** B\[i\] = A\[i+1\] **/** B\[i+1\] với mọi chỉ số i (0 ≤ i ≤ N-2).

Phép chia trong bài toán này là phép chia nguyên (tức là chỉ lấy phần nguyên của kết quả: ví dụ 5/3 = 1).

**Dữ liệu vào:**

Dòng đầu tiên là số lượng phần tử N (1 ≤ N ≤ 1000).

Dòng tiếp theo gồm N số nguyên A\[i\] (1 ≤ A\[i\] ≤ 2000).

**Kết quả:**

In ra một số nguyên là tổng các phần tử của dãy số B\[\] tìm được.

**Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 5  18 27 16 22 6 | 25 |

*Giải thích test: Dãy B\[\] tìm được là 5, 7, 5, 6, 2.*

### S48 - ĐẾM SỐ VẬT CẢN TRÊN MÊ CUNG

Một mê cung được mô tả dưới dạng ma trận ký tự trong đó dấu ‘.’ là mô tả ô trống, không có vật cản, dấu ‘#’ mô tả một vật cản. Các vật cản sẽ ghép lại với nhau thành vật cản lớn hơn nếu nó liền kề theo hàng hoặc cột.

Hãy đếm xem trong mê cung có bao nhiêu vật cản.

**Input**

Dong đầu ghi số hai số N, M là số hàng và số cột của mê cung.

N dòng tiếp theo mô tả mê cung trong đó chỉ có các ký tự ‘.’ và ‘#’.

**Output**

Ghi ra số vật cản đếm được.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 6  .#....  ..#...  ..#..#  ...##.  .#.... | 5 |

### S49 - SỐ MAY MẮN TIẾP THEO

Trong bài tập môn CTDL và GT, số may mắn được hiểu là số chỉ có hai chữ số 4 và 7. Với mỗi số nguyên dương N thì số may mắn tiếp theo của N được định nghĩa là số may mắn nhỏ nhất lớn hơn hoặc bằng N.

Cho hai số nguyên dương a và b (với a &lt;= b). Hãy tính tổng các số may mắn tiếp theo của tất cả các số trong đoạn \[a,b\]

**Input**

Chỉ có một dòng ghi hai số a,b (1 &lt;= a &lt;= b &lt;= 109).

**Output**

Ghi ra giá trị kết quả tính được.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2 7 | 33 |
| 7 7 | 7 |

### S50 - DÃY CON LIÊN TIẾP DÀI NHẤT

Cho dãy số A\[\] có N số nguyên và một số nguyên K.

Hãy tính độ dài dãy con liên tiếp dài nhất có thể trong dãy A\[\] sao cho trung bình cộng của dãy con đó lớn hơn hoặc bằng K.

**Input**

Dòng đầu ghi hai số N và K (1 &lt;= N &lt;= 106; |K| &lt;= 106 )

Dòng thứ hai ghi N số của dãy A\[\] ( |A\[i\]| &lt;= 106)

**Output**

Ghi ra độ dài dãy con liên tiếp dài nhất có trung bình cộng lớn hơn K.

(tức là nếu không tìm được dãy nào thỏa mãn thì ghi ra số 0).

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 7 3  1 5 2 3 1 4 1 | 5 |

### S54 - MIN VÀ MAX

Cho dãy số A\[\] có N phần tử là các số nguyên dương không quá 6 chữ số.

Người ta tạo ra ma trận C\[\]\[\] như sau:

- Kích thước của C là N\*N
- Với chỉ số tính từ 1 thì C\[i\]\[j\] = j \* min (A\[i\], A\[i+1\], …, A\[i+j-1\]).
 
với 1 &lt;= j &lt;=n; 1 &lt;= i &lt;= N – j + 1.

Hãy tìm **giá trị lớn nhất của ma trận C.**

**Input**

Dòng đầu ghi số N (1 &lt; N &lt;= 105).

Dòng tiếp theo ghi N số của dãy A\[\], các giá trị đều dương và không quá 106.

**Output**

Ghi ra giá trị lớn nhất tính được.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  1 4 6 3 2 | 9 |

### S55 - THỜI GIAN TỐI THIỂU

Có K công nhận được sắp xếp dọn dẹp một tòa nhà có N tầng. Để đảm bảo tính an toàn của dự án, công việc ở tầng thứ i sẽ phải hoàn thành trước khi bắt đầu dọn dẹp tầng thứ i+1. Các công nhân làm việc theo ca, mỗi tầng được giao cho ít nhất 1 công nhân. Sau khi tầng thứ i dọn xong, các công nhân phụ trách tầng thứ i+1 sẽ bắt đầu ngay công việc.

Lượng công việc ở tầng thứ i là A\[i\]. Nếu có C công nhân làm việc tại tầng A\[i\], thời gian hoàn thành công việc sẽ là A\[i\]/C (giờ) (giữ nguyên kết quả là số thập phân).

Các bạn hãy tính giúp chủ thầu xem thời gian tối thiểu để dọn dẹp xong tòa nhà là bao nhiêu?

**Input:**

Dòng đầu là 2 số nguyên N và K (1 &lt;= M &lt;= K &lt;= 10^12).

N dòng tiếp theo, mỗi dòng gồm một số nguyên A\[i\] (1 &lt;= A\[i\] &lt;= 10^12).

**Output:**

In ra số giờ tối thiểu để hoàn thành dự án. Làm tròn đáp án đến số tự nhiên gần nhất.

**Test ví dụ:**

 | Input | Output |
|---|---|
| 2 5  10  4 | 5 |

Giải thích test:

Sắp xếp 3 công nhân ở tầng I và 2 công nhân ở tầng II. Ta có round(10/3 + 4/2) = 5.

### S60 - DÃY SỐ VÔ HẠN

Một dãy số tự nhiên bắt đầu bởi con số 1 và được thực hiện N-1 phép biến đổi “gấp đôi” dãy số như sau: *Với dãy số A hiện tại, dãy số mới có dạng A, x, A trong đó x là số tự nhiên bé nhất chưa xuất hiện trong A.*

Ví dụ với 2 bước biến đổi, ta có \[1\] à \[1 2 1\] à \[1 2 1 3 1 2 1\]. Hãy xác định số thứ K trong dãy số cuối cùng là bao nhiêu?

**Input:** Dòng đầu tiên là số lượng bộ test T (T ≤ 20). Mỗi test gồm số nguyên dương N và K (1 ≤ N ≤ 50, 1 ≤ K ≤ 2N - 1).

**Output:** Với mỗi test, in ra đáp án trên một dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  3 2  4 8 | 2  4 |

Giải thích test 1: Dãy số thu được là \[1, 2, 1, 3, 1, 2, 1\].

Giải thích test 2: Dãy số thu được là \[1, 2, 1, 3, 1, 2, 1, 4, 1, 2, 1, 3, 1, 2, 1\].

### S62 - TỔNG CHỮ SỐ - 2

Cho hai số nguyên dương A và B. Tìm số N nhỏ nhất thỏa mãn: A là tổng các chữ số của N, B là tổng bình phương các chữ số của N. Nếu không tồn tại N thỏa mãn A và B hãy đưa ra -1. Giả thiết N có không quá 100 chữ số.

Ví dụ với A = 18, B = 162 ta tìm được số nhỏ nhất N=99 vì 9+9=18 và 92 + 92 = 162. Với A = 12, B = 9 ta có kết quả là -1.

**Input:** Dòng đầu tiên đưa vào số lượng bộ test T. Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là cặp số A, B được viết trên một dòng. T, A, B thỏa mãn ràng buộc: 1≤T≤100; 1≤A≤100; 1≤B≤10000.

**Output:** Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    18 162    12 9 | 99  -1 |

### SEQ5 - SEQ5

seq5

### T1291 - PHÉP CỘNG

Cho một phép toán có dạng **a + b = c** với a,b,c chỉ là các số nguyên dương có một chữ số. Hãy kiểm tra xem phép toán đó có đúng hay không.

**Dữ liệu vào:** Dòng đầu ghi số bộ test. Mỗi test chỉ có một dòng ghi ra phép toán (gồm đúng 9 ký tự)

**Kết quả:** Ghi ra YES nếu phép toán đó đúng. Ghi ra NO nếu sai.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  1 + 2 = 3  2 + 2 = 5 | YES  NO |

### T1300 - SỐ KHỐI LẬP PHƯƠNG

Một số X được gọi là số khối lập phương nếu X là lũy thừa bậc 3 của số Y (X= Y3). Cho số nguyên dương N, nhiệm vụ của bạn là tìm số khối lập phương lớn nhất bằng cách loại bỏ đi các chữ số của N. Ví dụ số 4125 ta có kết quả là 125 = 53.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một số tự nhiên N được viết trên một dòng.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤1018.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng. Nếu không tìm được đáp án in ra -1.
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2    4125    976 | 125    -1 |

### T1302 - PHÂN SỐ ĐƠN VỊ

Một phân số đơn vị nếu tử số của phân số đó là 1. Mọi phân số nguyên dương đều có thể biểu diễn thành tổng các phân số đơn vị. Ví dụ 2/3 = 1/2 + 1/6. Cho phân số nguyên dương P/Q bất kỳ (P &lt; Q), hãy biểu diễn phân số nguyên dương thành tổng phân số đơn vị.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là bộ đôi tử số P và mẫu số Q của phân số nguyên dương được viết trên một dòng.
- T, P, Q thỏa mãn ràng buộc: 1≤T≤100; 1≤P, Q≤100.
 
**Output:**

- Đưa ra đáp án tìm được trên 1 dòng, theo dạng “1/a + 1/b + …”
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2  2 3  1 3 | 1/2 + 1/6  1/3 |

### T1307 - BỐN ĐIỂM TRÊN MẶT PHẲNG

Cho 4 điểm trong không gian 3 chiều. Nhiệm vụ của bạn là kiểm tra xem chúng có cùng nằm trên một mặt phẳng hay không? Nếu có in ra “YES”, in ra “NO” trong trường hợp ngược lại.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 10000).

Mỗi test gồm 4 dòng, lần lượt là tọa độ nguyên x\[i\], y\[i\], z\[i\] của các điểm.

(-1000 &lt;= x\[i\], y\[i\], z\[i\] &lt;= 1000).

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

 | Input: | Output |
|---|---|
| 3  1 2 0  2 3 0  4 0 0  0 0 0  1 1 1  2 2 2  3 3 3  4 4 4  5 6 7  -8 -9 -10  12 19 0  3 1 5 | YES  YES  NO |

### T1308 - LẤY BỚT QUÂN CỜ

Trên bàn có C quân cờ. Có hai đối thủ chơi lần lượt. Mỗi lượt, người chơi sẽ lấy khỏi bàn từ 1 đến M quân cờ. Người thắng cuộc là người lấy được quân cờ cuối cùng.

Biết rằng hai người chơi đều chơi tối ưu. Hãy xác định xem ai là người thắng cuộc?

**Input:**

Dòng đầu tiên là số lượng bộ test T (T &lt;= 1000).

Mỗi test gồm 2 số nguyên C và M (0 &lt;= C &lt;= 1000, 1 &lt;= M &lt;= 1000).

**Output:**

In ra “First” nếu người đi trước là người chiến thắng, in ra “Second” nếu người chơi sau là người chiến thắng.

**Test ví dụ:**

 | Input: | Output |
|---|---|
| 4  20 9  1 5  7 5  0 3 | Second  First  First  Second |

## CÂY NHỊ PHÂN VÀ CÂY NHỊ PHÂN TÌM KIẾM

### 1410 - DUYỆT CÂY 1

Cho phép duyệt cây nhị phân Inorder và Preorder, hãy đưa ra kết quả phép duyệt Postorder của cây nhị phân. Ví dụ với cây nhị phân có các phép duyệt cây nhị phân của cây dưới đây:

Inorder : 4 2 5 1 3 6

Preorder: : 1 2 4 5 3 6

Postorder : 4 5 2 6 3 1

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 3 dòng: dòng đầu tiên đưa vào số N là số lượng node; dòng tiếp theo đưa vào N số theo phép duyệt Inorder; dòng cuối cùng đưa vào N số là kết quả của phép duyệt Preorder; các số được viết cách nhau một vài khoảng trống.
- T, N, node thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤1000; 1≤ giá trị node ≤104;
 
**Output:**

- Đưa ra kết quả phép duyệt Postorder theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  6    4 2 5 1 3 6  1 2 4 5 3 6 | 4 5 2 6 3 1 |

### 1411 - DUYỆT CÂY 2

Cho mảng A\[\] gồm N node là biểu diễn phép duyệt theo thứ tự giữa (Preorder) của cây nhị phân tìm kiếm. Nhiệm vụ của bạn là đưa ra phép duyệt theo thứ tự sau của cây nhị phân tìm kiếm.

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng node; dòng tiếp theo đưa vào N số A\[i\]; các số được viết cách nhau một vài khoảng trống.
- T, N, node thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤A\[i\]≤104;
 
**Output:**

- Đưa ra kết quả phép duyệt Postorder theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    5    40 30 35 80 100    8    40 30 32 35 80 90 100 120 | 35 30 100 80 40    35 32 30 120 100 90 80 40 |

### 1412 - DUYỆT CÂY 3

Cho cây nhị phân, nhiệm vụ của bạn là duyệt cây theo Level-order. Phép duyệt level-order trên cây là phép thăm node theo từng mức của cây. Ví dụ với cây dưới đây sẽ cho ta kết quả của phép duyệt level-order: 20 8 22 4 12 10 14.

![https://media.geeksforgeeks.org/wp-content/cdn-uploads/BinaryTree4.png](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả phép duyệt level-order theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    2    1 2 R 1 3 L    4    10 20 L 10 30 R 20 40 L 20 60 R | 1 3 2  10 0 30 40 60 |

### 1413 - DUYỆT CÂY 4

Cho hai mảng là phép duyệt Inorder và Level-order, nhiệm vụ của bạn là xây dựng cây nhị phân và đưa ra kết quả phép duyệt Postorder. Level-order là phép duyệt theo từng mức của cây. Ví dụ như cây dưới đây ta có phép Inorder và Level-order như dưới đây:

Inorder : 4 8 10 12 14 20 22

Level order: 20 8 22 4 12 10 14

![https://media.geeksforgeeks.org/wp-content/cdn-uploads/BinaryTree4.png](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 3 dòng: dòng đầu tiên đưa vào số N là số lượng node; dòng tiếp theo đưa vào N số là phép duyệt Inorder; dòng cuối cùng đưa vào N số là phép duyệt Level-order; các số được viết cách nhau một vài khoảng trống.
- T, N, node thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤A\[i\]≤104;
 
**Output:**

- Đưa ra kết quả phép duyệt Postorder theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    3    1 0 2     0 1 2     7    3 1 4 0 5 2 6     0 1 2 3 4 5 6 | 1 2 0  3 4 1 5 6 2 0 |

### 1414 - DUYỆT CÂY 5

Cho cây nhị phân, nhiệm vụ của bạn là duyệt cây theo xoắn ốc (spiral-order). Phép. Ví dụ với cây dưới đây sẽ cho ta kết quả của phép duyệt spiral-order: 1 2 3 4 5 6 7.

![spiral_order](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả phép duyệt level-order theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    2    1 2 R 1 3 L    4    10 20 L 10 30 R 20 40 L 20 60 R | 1 3 2  10 0 30 60 40 |

### 1415 - DUYỆT CÂY 6

Cho cây nhị phân, nhiệm vụ của bạn là duyệt cây theo mức đảo ngược (revese-level-order). Với cây dưới đây sẽ cho ta kết quả của phép duyệt theo mức đảo ngược là : 7 6 5 4 3 2 1.

![spiral_order](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả phép duyệt revese-level-order theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    2    1 2 R 1 3 L    4    10 20 L 10 30 R 20 40 L 20 60 R | 3 2 1  40 20 30 10 |

### 1416 - KIỂM TRA NODE LÁ

Cho cây nhị phân, nhiệm vụ của bạn là kiểm tra xem tất cả các node lá của cây có cùng một mức hay không? Ví dụ với cây dưới đây sẽ cho ta kết quả là Yes.

![spiral_order](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  2    1 2 R 1 3 L    4    10 20 L 10 30 R 20 40 L 20 60 R | 1    0 |

### 1417 - CÂY NHỊ PHÂN HOÀN HẢO

Cho cây nhị phân, nhiệm vụ của bạn là kiểm tra xem cây nhị phân có phải là một cây hoàn hảo hay không (perfect tree)? Một cây nhị phân được gọi là cây hoàn hảo nếu tất cả các node trung gian của nó đều có hai node con và tất cả các node lá đều có cùng một mức.

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3    6    10 20 L 10 30 R 20 40 L 20 50 R 30 60 L 30 70 R    2    18 15 L 18 30 R    5    1 2 L 2 4 R 1 3 R 3 5 L 3 6 R | Yes    Yes    No |

### 1418 - CÂY NHỊ PHÂN ĐỦ

Cho cây nhị phân, nhiệm vụ của bạn là kiểm tra xem cây nhị phân có phải là một cây đủ hay không (full binary tree)? Một cây nhị phân được gọi là cây đủ nếu tất cả các node trung gian của nó đều có hai node con.

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    4    1 2 L 1 3 R 2 4 L 2 5 R    3    1 2 L 1 3 R 2 4 L | 1    0 |

### 1419 - CÂY NHỊ PHÂN BẰNG NHAU

Cho hai cây nhị phân, nhiệm vụ của bạn là kiểm tra xem cây nhị phân có giống nhau hay không?

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 3 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái của mỗi cây; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    2    1 2 L 1 3 R    2    1 2 L 1 3 R    2    1 2 L 1 3 R    2    1 3 L 1 2 R | 1    0 |

### 1420 - TỔNG LỚN NHẤT

Cho cây nhị phân có giá trị mỗi node là một số, nhiệm vụ của bạn là tìm tổng lớn nhất từ một node lá này sang một node lá khác? Ví dụ với cây dưới đây ta có tổng lớn nhất là 27.

![tree](file:///C:/Users/Dell/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 3 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1    12    -15 5 L -15 6 R 5 -8 L 5 1 R -8 2 L -8 -3 R 6 3 L 6 9 R 9 0 R 0 4 L 0 -1 R -1 10 L | 27 |

### 1421 - BIẾN ĐỔI SANG CÂY NHỊ PHÂN TÌM KIẾM

Cho cây nhị phân, nhiệm vụ của bạn là dịch chuyển cây nhị phân thành cây nhị phân tìm kiếm. Phép dịch chuyển phải bảo toàn được cấu trúc cây nhị phân ban đầu.

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 3 dòng: dòng đầu tiên đưa vào số N là số lượng cạnh của cây; dòng tiếp theo đưa vào N bộ ba (u, v, x), trong đó u là node cha, v là node con, x= R nếu v là con phải, x=L nếu v là con trái; u, v, x được viết cách nhau một vài khoảng trống.
- T, N, u, v, thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤u, v≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng là phép duyệt Inorder của cây tìm kiếm.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    2    1 2 R 1 3 L    4    10 20 L 10 30 R 20 40 L 20 60 R | 1 2 3    10 20 30 40 60 |

### 1422 - XÂY DỰNG LẠI CÂY NHỊ PHÂN TÌM KIẾM

Cho một mảng là phép duyệt level-order của cây nhị phân tìm kiếm. Nhiệm vụ của bạn là xây dựng lại cây nhị phân tìm kiếm bảo toàn được cấu trúc cây nhị phân ban đầu.

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm dòng: dòng đầu tiên đưa vào số N là số lượng node của cây tìm kiếm; dòng tiếp theo đưa vào phép duyệt level-order của cây tìm kiếm; các số được viết cách nhau một vài khoảng trống.
- T, N, node thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤node≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng là phép duyệt Inorder của cây tìm kiếm.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    9    7 4 12 3 6 8 1 5 10    6    1 3 4 6 7 8 | 7 4 3 1 6 5 12 8 10    1 3 4 6 7 8 |

### 1423 - DUYỆT CÂY NHỊ PHÂN TÌM KIẾM 1

Cho một mảng A\[\] gồm N phần tử biểu diễn phép duyệt preorder của cây nhị phân tìm kiếm. Nhiệm vụ của bạn là đưa ra phép duyệt postorder của cây nhị phân tìm kiếm.

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng node của cây tìm kiếm; dòng tiếp theo đưa vào phép duyệt preorder của cây tìm kiếm; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤A\[i\]≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng là phép duyệt postorder của cây tìm kiếm.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    5    40 30 35 80 100    8    40 30 32 35 80 90 100 120 | 35 30 100 80 40    35 32 30 120 100 90 80 40 |

### 1424 - DUYỆT CÂY NHỊ PHÂN TÌM KIẾM 2

Cho một mảng A\[\] gồm N phần tử. Nhiệm vụ của bạn là đưa ra 1 nếu mảng A\[\] biểu diễn phép duyệt inorder của cây nhị phân tìm kiếm, ngược lại đưa ra 0.

 **Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào số N là số lượng node của cây tìm kiếm; dòng tiếp theo đưa vào N số A\[i\]; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤103; 1≤A\[i\]≤104;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3    5    10 20 30 40 50    6    90 80 100 70 40 30    3    1 1 2 | 1    0    0 |

### 1425 - NODE LÁ CỦA CÂY NHỊ PHÂN TÌM KIẾM

Cho dãy số gồm N số là phép duyệt theo thứ tự trước (Preorder) của một cây nhị phân tìm kiếm. Hãy in ra tất cả các node lá của cây ?

Ví dụ với dãy A\[\] = {30, 20, 15, 25, 23, 28, 40, 35, 33, 38, 45} là phép duyệt cây theo thứ tự trước sẽ cho ta kết quả: 15, 23, 28, 33, 38, 45.

 **Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T (T≤100).
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm 2 dòng: dòng thứ nhất là số tự nhiên N (N≤106). Dòng tiếp theo là N số là phép duyệt theo thứ tự trước của cây BST.
 
 **Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  6  10 5 1 7 40 50  11  30 20 15 25 23 28 40 35 33 38 45 | 1 7 50  15 3 28 33 38 45 |

### 1426 - NODE TRUNG GIAN CỦA CÂY NHỊ PHÂN TÌM KIẾM

Cho dãy số gồm N số là phép duyệt theo thứ tự trước (Preorder) của một cây nhị phân tìm kiếm. Hãy đưa ra số các node trung gian của cây ?

Ví dụ với dãy A\[\] = {30, 20, 15, 25, 23, 28, 40, 35, 33, 38, 45} là phép duyệt cây theo thứ tự trước sẽ cho ta kết quả là 5 bao gồm các node: 30, 20, 25, 40, 35.

 **Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T (T≤100).
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm 2 dòng: dòng thứ nhất là số tự nhiên N (N≤106). Dòng tiếp theo là N số là phép duyệt theo thứ tự trước của cây BST.
 
 **Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  6  10 5 1 7 40 50  11  30 20 15 25 23 28 40 35 33 38 45 | 3  5 |

### 1427 - ĐỘ SÂU CÂY NHỊ PHÂN TÌM KIẾM

Cho dãy số gồm N số là phép duyệt theo thứ tự trước (Preorder) của một cây nhị phân tìm kiếm. Hãy tìm độ sâu của cây ?

Ví dụ với dãy A\[\] = {30, 20, 15, 25, 23, 28, 40, 35, 33, 38, 45} là phép duyệt cây theo thứ tự trước sẽ cho ta kết quả là 3.

 **Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T (T≤100).
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm 2 dòng: dòng thứ nhất là số tự nhiên N (N≤106). Dòng tiếp theo là N số là phép duyệt theo thứ tự trước của cây BST.
 
 **Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  6  10 5 1 7 40 50  11  30 20 15 25 23 28 40 35 33 38 45 | 2  3 |

### 1428 - CÂY NHỊ PHÂN TÌM KIẾM CÂN BẰNG 1

Hãy xây dựng một cây nhị phân tìm kiếm cân bằng từ dãy số A\[\] =(a0, a1, .., an-1}. Đưa ra nội dung node gốc của cây tìm kiếm cân bằng. Ví dụ với dãy A\[\]={40, 28, 45, 38, 33, 15, 25, 20, 23, 35, 30} ta sẽ có cây nhị phân tìm kiếm cân bằng với node gốc là 33.

 **Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T (T≤100).
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm 2 dòng: dòng thứ nhất là số tự nhiên N (N≤106). Dòng tiếp theo là N số của mảng A\[\].
 
 **Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  11  40 28 45 38 33 15 25 20 23 35 30  10  1 2 3 4 5 6 7 8 9 10 | 30  5 |

### 1429 - CÂY NHỊ PHÂN TÌM KIẾM CÂN BẰNG 2

Hãy xây dựng một cây nhị phân tìm kiếm cân bằng từ dãy số A\[\] =(a0, a1, .., an-1}. Đưa ra phép duyệt theo thứ tự trước (preorder) của cây tìm kiếm cân bằng. Ví dụ với dãy A\[\]={40, 28, 45, 38, 33, 15, 25, 20, 23, 35, 30} ta sẽ có phép duyệt theo thứ tự trước của cây nhị phân tìm kiếm cân bằng với node gốc là 33 : 33, 25, 20, 15, 23, 28, 30, 40, 38, 35, 45.

 **Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T (T≤100).
- Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test gồm 2 dòng: dòng thứ nhất là số tự nhiên N (N≤106). Dòng tiếp theo là N số của mảng A\[\].
 
 **Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  11  40 28 45 38 33 15 25 20 23 35 30  10  1 2 3 4 5 6 7 8 9 10 | 30 23 15 20 25 28 38 33 35 40 45  5 2 1 3 4 8 6 7 9 10 |

## QUY HOẠCH ĐỘNG

### 1450 - BÀI 1. XÂU CON CHUNG DÀI NHẤT

Cho 2 xâu S1 và S2. Hãy tìm xâu con chung dài nhất của 2 xâu này *(các phần tử không nhất thiết phải liên tiếp nhau).*

**Input:** Dòng đầu tiên là số lượng bộ test T (T ≤ 20). Mỗi test gồm hai dòng, mô tả xâu S1 và S2, mỗi xâu có độ dài không quá 1000 và chỉ gồm các chữ cái in hoa.

**Output:** Với mỗi test, in ra độ dài dãy con chung dài nhất trên một dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2  AGGTAB  GXTXAYB  AA  BB | 4  0 |

Giải thích test 1: Dãy con chung là G, T, A, B.

### 1451 - DÃY CON LẶP LẠI DÀI NHẤT

Cho xâu ký tự S. Nhiệm vụ của bạn là tìm độ dài dãy con lặp lại dài nhất trong S. Dãy con có thể chứa các phần tử không liên tiếp nhau.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào độ dài xâu str; dòng tiếp theo đưa vào xâu S.
- T, str thỏa mãn ràng buộc: 1 ≤ T ≤ 100; 1 ≤ size(S) ≤ 100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    3    abc  5    axxxy | 0    2 |

### 1452 - DÃY CON CHUNG DÀI NHẤT CỦA BA XÂU

Cho ba xâu ký tự X, Y, Z. Nhiệm vụ của bạn là tìm độ dài dãy con chung dài nhất có mặt trong cả ba xâu.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào độ dài xâu X, Y, X; dòng tiếp theo đưa vào ba xâu X, Y, Z.
- T, X, Y, Z thỏa mãn ràng buộc: 1 ≤ T ≤ 100; 1 ≤ size(X), size(Y), size(Z) ≤ 100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5 8 13  geeks geeksfor geeksforgeeks  7 6 5  abcd1e2 bc12ea bd1ea | 5  3 |

### 1453 - BÀI 4. DÃY CON TĂNG DÀI NHẤT

Cho một dãy số nguyên gồm N phần tử A\[1\], A\[2\], ... A\[N\].

Biết rằng dãy con tăng là 1 dãy A\[i1\],... A\[ik\]

thỏa mãn i1 &lt; i2 &lt; ... &lt; ik và A\[i1\] &lt; A\[i2\] &lt; .. &lt; A\[ik\].

Hãy cho biết dãy con tăng dài nhất của dãy này có bao nhiêu phần tử?

**Input:** Dòng 1 gồm 1 số nguyên là số N (1 ≤ N ≤ 1000). Dòng thứ 2 ghi N số nguyên A\[1\], A\[2\], .. A\[N\] (1 ≤ A\[i\] ≤ 1000).

**Output:** Ghi ra độ dài của dãy con tăng dài nhất.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 6  1 2 5 4 6 2 | 4 |

### 1454 - BÀI 5. TỔNG LỚN NHẤT CỦA DÃY CON TĂNG DẦN

Cho dãy số A\[\] gồm N số. Nhiệm vụ của bạn là tìm tổng lớn nhất của dãy con được sắp theo thứ tự tăng dần của dãy A\[\]. Ví dụ với dãy A\[\] = {1, 101, 2, 3, 100, 4, 5} ta có kết quả là 106 = 1 + 2 + 3 + 100. Với dãy A\[\] = {10, 7, 5} ta có kết quả là 10. Với dãy A\[\] = {1, 2, 3, 5} ta có kết quả là 11.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào N là số phần tử của dãy A\[\]; dòng tiếp theo đưa vào N số A\[i\]; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤103; 0≤A\[i\] ≤103.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 3  7  1 101 2 3 100 4 5  3  10 7 5  4  1 2 3 5 | 106  10  11 |

### 1455 - BÀI 6. SỐ BƯỚC ÍT NHẤT

Cho mảng A\[\] gồm N số nguyên. Nhiệm vụ của bạn là sắp xếp lại mảng số với số lượng bước là ít nhất. Tại mỗi bước, bạn chỉ được phép chèn phần tử bất kỳ của mảng vào vị trí bất kỳ trong mảng. Ví dụ A\[\] = {2, 3, 5, 1, 4, 7, 6 }sẽ cho ta số phép chèn ít nhất là 3 bằng cách lấy số 1 chèn trước số 2, lấy số 4 chèn trước số 5, lấy số 6 chèn trước số 7 ta nhận được mảng được sắp.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là một số N; dòng tiếp theo đưa vào N số của mảng A\[\]; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤1000; 1≤A\[i\] ≤1000.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 1    7    2 3 5 1 4 7 6 | 3 |

### 1456 - BÀI 7. CON ẾCH

Một con ếch có thể nhảy 1, 2, 3 bước để có thể lên đến một đỉnh cần đến. Hãy đếm số các cách con ếch có thể nhảy đến đỉnh.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là số n là số bước con ếch có thể lên được đỉnh.
- T, n thỏa mãn ràng buộc: 1≤T≤100; 1≤n ≤50.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| Input | Output |
|---|---|
| 2    1    5 | 1    13 |

### 1457 - BÀI 8. TỔ HỢP C(N, K)

Cho 2 số nguyên n, k. Bạn hãy tính C(n, k) modulo 109+7.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test gồm 2 số nguyên n, k (1 ≤ k ≤ n ≤ 1000).

**Output:**

- Với mỗi test, in ra đáp án trên một dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2  5 2  10 3 | 10  120 |

### 1458 - BÀI 9. BẬC THANG

Một chiếc cầu thang có N bậc. Mỗi bước, bạn được phép bước lên trên tối đa K bước. Hỏi có tất cả bao nhiêu cách bước để đi hết cầu thang? (Tổng số bước đúng bằng N).

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 100).
- Mỗi test gồm hai số nguyên dương N và K(1 ≤ N ≤ 100000, 1 ≤ K ≤ 100).

**Output:**

- Với mỗi test, in ra đáp án tìm được trên một dòng theo modulo 109+7.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2  2 2  4 2 | 2  5 |

Giải thích test 1: Có 2 cách đó là (1, 1) và (2).

Giải thích test 2: 5 cách đó là: (1, 1, 1, 1), (1, 1, 2), (1, 2, 1), (2, 1, 1), (2, 2).

### 1459 - XÂU CON ĐỐI XỨNG DÀI NHẤT

Cho xâu S chỉ bao gồm các ký tự viết thường và dài không quá 1000 ký tự.

Hãy tìm xâu con đối xứng dài nhất của S.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test gồm một xâu S có độ dài không vượt quá 1000, chỉ gồm các kí tự thường.
 
**Output:** Với mỗi test, in ra đáp án tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  abcbadd  aaaaa | 5  5 |

### 1460 - BÀI 11. XÂU ĐỐI XỨNG 1

Cho xâu ký tự str. Nhiệm vụ của bạn là tìm số phép chèn tối thiểu các ký tự vào str để str trở thành xâu đối xứng. Ví dụ: str =”ab” ta có số phép chèn tối thiểu là 1 để trở thành xâu đối xứng “aba” hoặc “bab”. Với xâu str=”aa” thì số phép chèn tối thiểu là 0. Với xâu str=”abcd” có số phép chèn tối thiểu là 3 để trở thành xâu “dcbabcd”

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu ký tự được viết trên một dòng
- T, str thỏa mãn ràng buộc: 1≤T≤100; 1≤length(str)≤40.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 3    abcd    aba    geeks | 3    0  3 |

### 1461 - BÀI 12. XÂU ĐỐI XỨNG 2

Cho xâu ký tự S. Nhiệm vụ của bạn là tìm số phép loại bỏ ít nhất các ký tự trong S để S trở thành xâu đối xứng. Chú ý, phép loại bỏ phải bảo toàn tính trước sau của các ký tự trong S.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu ký tự được viết trên một dòng
- T, str thỏa mãn ràng buộc: 1≤T≤100; 1≤length(S)≤100.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    aebcbda    geeksforgeeks | 2    8 |

### 1462 - BÀI 13. XEM PHIM

John có một đàn bò. Một ngày đẹp trời, anh ta quyết định mua xe tải với khả năng chở được C kg (1000 ≤ C ≤ 25000) để đưa những con bò đi xem phim. Cho số con bò là N (20 ≤ N ≤ 100) và khối lượng w\[i\] của từng con (đều nhỏ hơn C), hãy cho biết **khối lượng bò lớn nhất** mà John có thể đưa đi xem phim là bao nhiêu.

**Input:**

- Dòng 1: 2 số nguyên C và N cách nhau bởi dấu cách
- Dòng 2..N+1: Ghi lần lượt các số nguyên: w\[i\]

**Output:**

- Một số nguyên là tổng khối lượng bò lớn nhất mà John có thể mang đi xem phim.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 259 5  81  58  42  33  61 | 242 |

### 1463 - BÀI 14. CÁI TÚI

Một người có cái túi thể tích V (V&lt;1000). Anh ta có N đồ vật cần mang theo (N≤1000), mỗi đồ vật có thể tích là A\[i\] (A\[i\]≤100) và giá trị là C\[i\] (C\[i\]≤100). Hãy xác định tổng giá trị lớn nhất của các đồ vật mà người đó có thể mang theo, sao cho tổng thể tích không vượt quá V.

**Input**

- Dòng đầu ghi số bộ test T (T&lt;10)
- Mỗi bộ test gồm ba dòng. Dòng đầu ghi 2 số N và V. Dòng tiếp theo ghi N số của mảng A. Sau đó là một dòng ghi N số của mảng C.
- Dữ liệu vào luôn đảm bảo không có đồ vật nào có thể tích lớn hơn V.

**Output**

- Với mỗi bộ test, ghi trên một dòng giá trị lớn nhất có thể đạt được.

**Ví dụ**

| **Input** | **Output** |
|---|---|
| 1  15 10  5 2 1 3 5 2 5 8 9 6 3 1 4 7 8  1 2 3 5 1 2 5 8 7 4 1 2 3 2 1 | 15 |

### 1465 - BÀI 16. KÝ TỰ GIỐNG NHAU

Giả sử bạn cần viết N ký tự giống nhau lên màn hình. Bạn chỉ được phép thực hiện ba thao tác dưới đây với chi phí thời gian khác nhau:

- Thao tác insert: chèn một ký tự với thời gian là X.
- Thao tác delete: loại bỏ ký tự cuối cùng với thời gian là Y.
- Thao tác copying: copy và paste tất cả các ký tự đã viết để số ký tự được nhân đôi với thời gian là Z.

Hãy tìm thời gian ít nhất để có thể đưa ra màn hình N ký tự giống nhau. Ví dụ với N = 9, X =1, Y = 2, Z =1 ta có kết quả là 5 bằng cách thực hiện: insert, insert, copying, copying, insert.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào N là số các ký tự giống nhau cần viết lên màn hình; dòng tiếp theo đưa vào bộ ba số X, Y, Z tương ứng với thời gian thực hiện ba thao tác; các số được viết cách nhau một vài khoảng trống.
- T, N, X, Y, Z thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤100; 1≤X, Y, Z ≤100.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    9    1 2 1    10    2 5 4 | 5    14 |

### 1466 - BÀI 17. TỔNG CÁC XÂU CON

Cho số nguyên dương N được biểu diễn như một xâu ký tự số. Nhiệm vụ của bạn là tìm tổng của tất cả các số tạo bởi các xâu con của N. Ví dụ N=”1234” ta có kết quả là 1670 = 1 + 2 + 3 + 4 + 12 + 23 + 34 + 123 + 234 + 1234.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một số N.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤1012.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    1234    421 | 1670    491 |

### 1467 - BÀI 18. TỔNG BẰNG K

Cho một mảng A\[\] gồm N số nguyên và số K. Tính số cách lấy tổng các phần tử của A\[\] để bằng K. Phép lấy lặp các phần tử hoặc sắp đặt lại các phần tử được chấp thuận. Ví dụ với mảng A\[\] = {1, 5, 6}, K = 7 ta có 6 cách sau:

7 = 1 + 1 + 1+1 + 1 + 1+1 (lặp số 1 7 lần)

7 = 1 + 1 + 5 (lặp số 1)

7 = 1 + 5 + 1 (lặp và sắp đặt lại số 1)

7 = 1 + 6

7 = 6 + 1

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào N và K; dòng tiếp theo đưa vào N số của mảng A\[\]; các số được viết cách nhau một vài khoảng trống.
- T, N, K, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤1000; 1≤A\[i\]≤100.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng. Khi kết quả quá lớn đưa ra kết quả dưới dạng modulo với 109+7.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    3 7    1 5 6    4 14    12 3 1 9 | 6    150 |

### 1468 - BÀI 19. GIẢI MÃ

Một bản tin M đã mã hóa bí mật thành các con số theo ánh xạ như sau: ‘A’-&gt;1, ‘B’-&gt;2, .., ‘Z’-&gt;26. Hãy cho biết có bao nhiêu cách khác nhau để giải mã bản tin M. Ví dụ với bản mã M=”123” nó có thể được giải mã thành ABC (1 2 3), LC (12 3), AW(1 23).

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu ký tự số M.
- T, M thỏa mãn ràng buộc: 1≤T≤100; 1≤length(M)≤40.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    123    2563 | 3    2 |

### 1469 - BÀI 20. TỔNG BÌNH PHƯƠNG

Mọi số nguyên dương N đều có thể phân tích thành tổng các bình phương của các số nhỏ hơn N. Ví dụ số 100 = 102 hoặc 100 = 52 + 52 + 52 + 52. Cho số nguyên dương N. Nhiệm vụ của bạn là tìm số lượng ít nhất các số nhỏ hơn N mà có tổng bình phương bằng N.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi test là một số tự nhiên N được viết trên 1 dòng.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤10000.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 3    100    6    25 | 1    3    1 |

### 1470 - HÌNH VUÔNG LỚN NHẤT

Cho một bảng số N hàng, M cột chỉ gồm 0 và 1. Bạn hãy tìm hình vuông có kích thước lớn nhất, sao cho các số trong hình vuông toàn là số 1.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test bắt đầu bởi 2 số nguyên N, M (1 ≤ N, M ≤ 500).
- N dòng tiếp theo, mỗi dòng gồm M số mô tả một hàng của bảng.
 
**Output:**

- Với mỗi test, in ra đáp án là kích thước của hình vuông lớn nhất tìm được trên một dòng.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  6 5  0 1 1 0 1  1 1 0 1 0  0 1 1 1 0  1 1 1 1 0  1 1 1 1 1  0 0 0 0 0  2 2  0 0  0 0 | 3  0 |

## THUẬT TOÁN QUY HOẠCH ĐỘNG

### 1464 - BÀI 15. BÀI TOÁN CÁI TÚI KHÔNG NGUYÊN

Một trong những bài toán kinh điển của lý thuyết tổ hợp là Bài toán cái túi. Bài toán được phát biểu như sau: Một nhà thám hiểm cần đem theo một cái túi trọng lượng không quá W. Có N đồ vật cần đem theo. Đồ vật thứ i có trọng lượng A\[i\], có giá trị sử dụng C\[i\]. Nhiệm vụ của bạn là hãy tìm cách đưa đồ vật vào túi cho nhà thám hiểm sao cho tổng giá trị sử dụng các đồ vật trong túi là lớn nhất. Giả thiết với mỗi vật dụng, ta có thể chia nhỏ chúng ra thành nhiều phần khác nhau (Fraction Knapsack).

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào hai số N, W tương ứng với số lượng đồ vật và trọng lượng túi; phần thứ 2 đưa vào 2\*N số tương ứng với trọng lượng đồ vật A\[i\] và giá trị sử dụng C\[i\] của mỗi đồ vật.
- T, N, W, A\[i\], C\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N, W≤100; 1≤A\[i\], C\[i\]≤100.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng, in ra 2 chữ số sau dấu phảy.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    3 50    60 10  100 20  120 30    2 50    60 10  100 20 | 240.00    160.00 |

### 1471 - BÀI 22. ĐƯỜNG ĐI NHỎ NHẤT

Cho bảng A\[\] kích thước N x M (N hàng, M cột). Bạn được phép đi xuống dưới, đi sang phải và đi xuống ô chéo dưới. Khi đi qua ô (i, j), điểm nhận được bằng A\[i\]\[j\].

Hãy tìm đường đi từ ô (1, 1) tới ô (N, M) sao cho tổng điểm là nhỏ nhất.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test gồm số nguyên dương N và M.
- N dòng tiếp theo, mỗi dòng gồm M số nguyên A\[i\]\[j\] (0 ≤ A\[i\] ≤ 1000).

**Output:**

- Với mỗi test, in ra độ dài dãy con tăng dài nhất trên một dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 1  3 3  1 2 3  4 8 2  1 5 3 | 8 |

Giải thích test: Đường đi (1, 1) à (1, 2) à (2, 3) à (3, 3).

### 1474 - BÀI 25. SO SÁNH XÂU CON

Cho một xâu S và Q truy vấn. Mỗi truy vấn có dạng a b c d yêu cầu bạn so sánh 2 xâu con từ vị trí aà b và cà d. In ra “YES” nếu bạn có thể sắp xếp lại các kí tự của 2 xâu con sao cho 2 xâu mới thu được giống nhau, in ra “NO” trong trường hợp ngược lại.

**Input:** Dòng đầu tiên là số nguyên N (1 ≤ N ≤ 50 000).

Dòng tiếp theo là số lượng truy vấn Q (1 ≤ Q ≤ 50 000).

Q dòng tiếp theo, mỗi dòng gồm 4 số nguyên a b c d.

**Output:** Với mỗi truy vấn in ra đáp án tìm được trên một dòng.

**Ví dụ:**

| **Test 1** | **Test 2** |
|---|---|
| Input:  abbbabba  2  3 5 2 4  1 2 6 7  Output:  NO    NO | Input:  acmptit  2  1 2 5 6  5 5 7 7  Output:  NO    YES |

*Giải thích test 1: Truy vấn 1: bba – bbb. Truy vấn 2: ab – bb*

### S101 - TÍNH P(N,K)

P(n, k) là số phép biểu diễn các tập con có thứ tự gồm k phần tử của tập gồm n phần tử. Số P(n, k) được định nghĩa theo công thức sau:

![](data:image/png;base64,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)

Cho số hai số n, k. Hãy tìm P(n,k) theo modulo 109+7.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một cặp số n, k được viết trên một dòng.
- T, n, k thỏa mãn ràng buộc: 1 ≤ T ≤ 100; 1 ≤ n,k ≤ 1000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    5 2    4 2 | 20    12 |

### S102 - TẬP CON BẰNG NHAU

Cho tập các số A\[\] = (a1, a2, .., an). Hãy kiểm tra xem ta có thể chia tập A\[\] thành hai tập con sao cho tổng các phần tử của hai tập con bằng nhau hay không. Đưa ra YES nếu có thể thực hiện được, ngược lại đưa ra NO.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào số N là số lượng phần tử của dãy số A\[\]; dòng tiếp theo đưa vào N phần tử của dãy số A\[\].
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T ≤100; 1≤N≤100; 1≤ A\[i\] ≤100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 | Input | Output |
|---|---|
| 2    4    1 5 11 5    3    1 3 5 | YES    NO |

### S103 - TỔNG BÌNH PHƯƠNG

Mọi số nguyên dương N đều có thể phân tích thành tổng các bình phương của các số nhỏ hơn N. Ví dụ số 100 = 102 hoặc 100 = 52 + 52 + 52 + 52. Cho số nguyên dương N. Nhiệm vụ của bạn là tìm số lượng ít nhất các số nhỏ hơn N mà có tổng bình phương bằng N.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi test là một số tự nhiên N được viết trên 1 dòng.
- T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤10000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3    100    6    25 | 1    3    1 |

### S104 - DÃY SỐ BI-TONIC

Một dãy số được gọi là Bi-tonic nếu nó được chia thành hai dãy đầu tăng dần và dãy tiếp theo giảm dần. Nhiệm vụ của bạn là tìm tổng lớn nhất dãy con Bi-tonic của dãy số A\[\]. Ví dụ với dãy A\[\] = {1, 15, 51, 45, 33, 100, 12, 18, 9} ta có kết quả là 194 tương ứng với dãy Bi-tonic {1, 15, 51, 100, 18, 9}.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào N là số phần tử của dãy A\[\]; dòng tiếp theo đưa vào N số A\[i\]; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤100; 0≤A\[i\] ≤100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    6    80 60 30 40 20 10    9    1 15 51 45 33 100 12 18 9 | 210    194 |

### S105 - TỔNG CHỮ SỐ

Cho hai số nguyên dương A và B. Tìm số N nhỏ nhất thỏa mãn: A là tổng các chữ số của N, B là tổng bình phương các chữ số của N. Nếu không tồn tại N thỏa mãn A và B hãy đưa ra -1. Giả thiết N có không quá 100 chữ số.

Ví dụ với A = 18, B = 162 ta tìm được số nhỏ nhất N=99 vì 9+9=18 và 92 + 92 = 162. Với A = 12, B = 9 ta có kết quả là -1.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là cặp số A, B được viết trên một dòng.
- T, A, B thỏa mãn ràng buộc: 1≤T≤100; 1≤A≤100; 1≤B≤10000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    18 162    12 9 | 99  -1 |

### S106 - GIẢI MÃ

Một bản tin M đã mã hóa bí mật thành các con số theo ánh xạ như sau: ‘A’-&gt;1, ‘B’-&gt;2, .., ‘Z’-&gt;26. Hãy cho biết có bao nhiêu cách khác nhau để giải mã bản tin M. Ví dụ với bản mã M=”123” nó có thể được giải mã thành ABC (1 2 3), LC (12 3), AW(1 23).

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu ký tự số M.
- T, M thỏa mãn ràng buộc: 1≤T≤100; 1≤length(M)≤40.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    123    2563 | 3    2 |

### S107 - ĐƯỜNG ĐI NHỎ NHẤT - 1

Cho bảng A\[\] kích thước N x M (N hàng, M cột).

Bạn được phép **đi xuống dưới, đi sang phải và đi xuống ô chéo dưới**. Khi đi qua ô (i, j), điểm nhận được bằng A\[i\]\[j\].

Hãy tìm đường đi từ ô (1, 1) tới ô (N, M) sao cho tổng điểm là nhỏ nhất.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test gồm số nguyên dương N và M (1 &lt; N, M &lt; 500)
- N dòng tiếp theo, mỗi dòng gồm M số nguyên A\[i\]\[j\] (0 ≤ A\[i\] ≤ 1000).
 
**Output:**

- Với mỗi test, in ra giá trị tổng điểm nhỏ nhất tìm được trên một dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  3 3  1 2 3  4 8 2  1 5 3 | 8 |

Giải thích test: Đường đi (1, 1) - (1, 2) - (2, 3) - (3, 3).

### S108 - ĐƯỜNG ĐI NHỎ NHẤT - 2

Cho một bảng số kích thước N x M. Chi phí khi đi qua ô (i,j) bằng A\[i\]\[j\]. Nhiệm vụ của bạn là hãy tìm một đường đi từ ô (1, 1) tới ô (N, M) sao cho chi phí là nhỏ nhất.

Tại mỗi ô, bạn được phép **đi sang trái, sang phải, đi lên trên và xuống dưới**.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi hai số nguyên N và M (1 ≤ N, M ≤ 500).
- N dòng tiếp theo, mỗi dòng gồm M số nguyên A\[i\]\[j\] (0 ≤ A\[i\]\[j\] ≤ 9).
 
**Output:**

- Với mỗi test, in ra một số nguyên là chi phí nhỏ nhất cho đường đi tìm được.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 3  4  5  0 3 1 2 9  7 3 4 9 9  1 7 5 5 3  2 3 4 2 5  1  6  0 1 2 3 4 5  5 5  1 1 1 9 9  9 9 1 9 9  1 1 1 9 9  1 9 9 9 9  1 1 1 1 1 | 24  15  13 |

### S111 - DÃY CON TĂNG DÀI NHẤT 2 CHIỀU

Cho N cặp số Ai (xi, yi). Cặp (x1, y1) &lt; (x2,y2) nếu như x1 &lt; x2 và y1 &lt; y2.

Nhiệm vụ của bạn là hãy tìm dãy con tăng dài nhất trên mảng các cặp số này.

**Input:**

Dòng đầu tiên là số nguyên N (N &lt;= 100 000).

N dòng tiếp theo, mỗi dòng gồm 2 số nguyên xi, yi. Các số có giá trị tuyệt đối không vượt quá 109.

**Output:**

In ra một số nguyên là độ dài dãy con tăng dài nhất tìm được.

 | Input: | Output |
|---|---|
| 8  1 3  3 2  1 1  4 5  6 3  9 9  8 7  7 6 | 3 |

### S112 - CHIA HẾT

Cho một dãy số T gồm N phần tử T1, T2, … , TN phân biệt. Một số nguyên dương được gọi là số phù hợp với dãy T nếu tổng các chữ số của nó chia hết cho một trong N số Ti.

Hãy đếm số lượng các số phù hợp với dãy T trong đoạn \[L, R\].

**Input**

Dòng đầu tiên gồm một số nguyên dương Q (1 ≤ Q ≤ 20) là số lượng truy vấn.

Mỗi truy vấn có dạng như sau:

Dòng đầu tiên gồm 2 số nguyên L, R (1 ≤ L ≤ R ≤ 1018).

Dòng thứ hai gồm 1 số nguyên N (1 ≤ N ≤ 10).

Dòng thứ 3 gồm N số nguyên T1, T2, … , TN (1 ≤ Ti ≤ 50). Các giá trị của Ti phân biệt.

**Output**

Với mỗi truy vấn, in ra kết quả tính được trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  1 20  1  2  1 21  2  2 3  15 | 10  15 |

**Giải thích:** Ở truy vấn đầu tiên, các số thoả mãn là 2, 4, 6, 8, 11, 13, 15, 17, 19, 20.

### S113 - XÂU ĐỐI XỨNG - 3

Xâu đối xứng là xâu mà khi ta đảo ngược thứ tự của xâu thì nhận lại được xâu cũ.

**Xâu tốt** là xâu mà mỗi ký tự của nó thuộc về ít nhất 1 xâu đối xứng có độ dài lớn hơn 1.

Ví dụ: AABBAA, AABA,.. là các xâu tốt.

Giá sử cho xâu s chỉ có 2 ký tự A và B. Hãy đếm số xâu con là xâu tốt trong s ( Xâu con là dãy các phần tử liền kề nhau của xâu gốc ).

**Input:**

Dòng đầu là số ký tự của s ( Không vượt quá 105)

Dòng thứ 2 là xâu S chỉ gồm các ký tự A và B

**Ouput**

Ghi ra kết quả đếm được

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 7  BABBAAB | 13 |
| 6  BAABBA | 8 |

### S114 - TRÒ CHƠI DÒ MÌN

![Dò min Windows XP cho Android - Tải về APK](data:image/jpeg;base64,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)

Hầu hết chúng ta đã quen thuộc với trò chơi Dò mìn trên Windows.

Mỗi ô hoặc là chưa biết, hoặc là chứa mìn, hoặc là chứa số lượng số các quả mìn xung quanh chúng.

Ở phiên bản dễ hơn của trò chơi này. Bàn chơi là một đường thẳng.

Cũng với quy tắc như vậy. Ô nào có mìn được đánh dấu là \*, chưa biết là ? nếu biết chắc chắn rằng không chứa mìn thì sẽ có giá trị là số mìn xung quanh nó ( Vì là đường thẳng nên số mìn xung quanh chỉ có thể là 0, 1 hoặc 2).

Ví dụ một dãy hợp lệ: ?1?\*101\*2\*

 Yêu cầu: Hãy tìm **số cách** đặt ký tự hợp lệ vào tất cả các ô chưa biết ( ô có chứa dấu ? ) sao cho dãy sau khi điền là hợp lệ.

**Input:**

Xâu ký tự có độ dài không vượt quá 106 ký tự.

**Output:**

Gồm một dòng duy nhất ghi kết quả của bài toán.

 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| \*2\*? | 2 |
| ?1?\*101\*2\* | 2 |

Giải thích test:

Test 1: 2 ký tự có thể điền là 1 hoặc \*

Test 2: 2 ký tự có thể điền là \*1 hoặc 0\*

### S115 - BÀI TOÁN CÁI TÚI KHÔNG NGUYÊN

Một trong những bài toán kinh điển của lý thuyết tổ hợp là Bài toán cái túi. Bài toán được phát biểu như sau: Một nhà thám hiểm cần đem theo một cái túi trọng lượng không quá W. Có N đồ vật cần đem theo. Đồ vật thứ i có trọng lượng A\[i\], có giá trị sử dụng C\[i\]. Nhiệm vụ của bạn là hãy tìm cách đưa đồ vật vào túi cho nhà thám hiểm sao cho tổng giá trị sử dụng các đồ vật trong túi là lớn nhất. Giả thiết với mỗi đồ vật, ta có thể chia nhỏ chúng ra thành nhiều phần khác nhau (Fraction Knapsack).

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào hai số N, W tương ứng với số lượng đồ vật và trọng lượng túi; phần thứ 2 đưa vào 2\*N số tương ứng với trọng lượng đồ vật A\[i\] và giá trị sử dụng C\[i\] của mỗi đồ vật.
- T, N, W, A\[i\], C\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N, W≤100; 1≤A\[i\], C\[i\]≤100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng, in ra 2 chữ số sau dấu phảy.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    3 50    60 10  100 20  120 30    2 50    60 10  100 20 | 240.00    160.00 |

### S126 - NGÂN HÀNG

Một ngân hàng muốn dành ra N đồng để cho sinh viên vay vốn ưu đãi và có m sinh viên đăng ký, sinh viên thứ i đăng ký vay ti đồng. Ngân hàng muốn đáp ứng được nhiều sinh viên nhất nhưng phải đảm bảo nếu sinh viên thứ i được cho vay thì phải vay đúng ti đồng.

Trong các cách thỏa mãn, ngân hàng muốn chọn cách mà số sinh viên vay ít nhất là lớn nhất.

**Yêu cầu:** Cho t1,t2,…,tm và lần lượt Q giá trị N giả định.

Với mỗi giá trị N, hãy đưa ra cách cho vay thỏa mãn yêu cầu đề bài.

**Input**

Dòng đầu ghi 2 số m và Q (m,Q ≤ 9000).

Dòng thứ 2 ghi m số nguyên dương t1 … tm (0 &lt; ti ≤ 109)

Dòng thứ 3 ghi Q giá trị N giả định (0 &lt; Ni ≤ 1018)

**Output**

Gồm Q dòng, mỗi dòng ghi 2 số s,v lần lượt là số sinh viên được vay vốn và số tiền sinh viên được vay ít nhất ứng với giá trị N giả định.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 2  1 3 2 3 5  6 8 | 3 1  3 2 |

### S128 - PHẦN TỬ CHỐT

Cho dãy số A\[\] gồm có N phần tử. Phần tử A\[i\] được gọi là phần tử Pivot (hay phần tử chốt) nếu như nó phân hoạch dãy số thành 2 phần:

- Các phần tử bên trái có giá trị nhỏ hơn hoặc bằng A\[i\],
- Các phần tử bên phải có giá trị lớn hơn A\[i\].
 
Với dãy số A\[\] = {2, 1, 3, 4, 6, 5, 7}, có 3 phần tử chốt là 3, 4, 7. Với phần tử 3, ta có phân hoạch {2, 1}, 3 và {4, 6, 5, 7} thỏa mãn các tính chất nêu trên. Với phần tử 7, tập hợp các phần tử bên phải là một tập rỗng nên cũng thõa mãn yêu cầu.

Việc xác định được phần tử chốt đóng vai trò quan trọng trong thuật toán Quicksort. Các bạn hãy xác định xem dãy số đã cho có bao nhiêu phần tử chốt?

**Input:**

Dòng đầu tiên là số lượng bộ test (T ≤ 10).

Dòng test bắt đầu bởi số nguyên N (1 ≤ N ≤ 100 000) là số lượng phần tử của dãy số.

Dòng tiếp theo gồm N phần tử A\[i\] (0 ≤ A\[i\] ≤ 109).

**Output:**

In ra đáp án là số lượng phần tử chốt tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  3  1 1 1  3  1 2 3  7  2 1 3 4 6 5 7 | 1  3  3 |

### S130 - CẶP SỐ ĐẶC BIỆT

Cho dãy số nguyên A có n phần tử.

Hãy đếm xem có bao nhiêu cặp (i,j) thỏa mãn:

- i &lt; j
- A\[i\] &gt; A\[j\] và đều là số chẵn
- Tồn tại chỉ số k với i &lt; k &lt; j sao cho A\[k\] là số lẻ
 
**Input**

Dòng đầu tiên ghi số n (1 ≤ n ≤ 105).

**Output**

Dòng thứ 2 ghi n số của dãy A, các giá trị A\[i\] không vượt quá 106.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5  4 3 2 5 1 | 1 |

### S132 - MA TRẬN CON LỚN NHẤT

Giả sử giá trị của một ma trận là hiệu giữa tổng các số trên đường chéo chính và tổng các số trên đường chéo phụ. Cho ma trận A kích thước N \* N, hãy tìm ma trận con của A sao cho ma trận con đó có giá trị lớn nhất.

**Input**

Dòng đầu ghi số N (2 ≤ N ≤ 400)

N dòng tiếp theo ghi ma trận A. Các số trong đoạn \[-1000, 1000\].

**Output**

Ghi ra giá trị lớn nhất tìm được.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 4  9 -2 -8 0  -6 -2 0 -9  4 -5 6 1  1 3 4 9 | 26 |

### S134 - BÀI TOÁN CHỮ SỐ - 1

Cho 2 số nguyên A, B. Nhiệm vụ của bạn là hãy đếm xem mỗi chữ số sẽ xuất hiện bao nhiêu lần nếu như liệt kê tất cả các số từ A đến B.

**Input**

- Số đầu tiên là số lượng bộ test T (T ≤ 5000). Mỗi test gồm 2 số nguyên A và B.
- 1 ≤ A ≤ B ≤ 108.
 
**Output**

- Với mỗi test, hãy in ra trên một dòng 10 số nguyên, là tần số xuất hiện của các chữ số từ 0 đến 9.
 
**Example**

 | **Input** | **Output** |
|---|---|
| 3  1 9  10 456  123 2437 | 0 1 1 1 1 1 1 1 1 1  85 195 195 195 152 92 85 84 84 84  661 1738 1206 770 700 662 662 662 661 661 |

### S15 - CHIA ĐÔI

Ngày lễ Valentine, Nam mang hộp socola đến nhà bạn gái để tặng nhưng bạn gái từ chối. Nam đành phải mang về ăn dần. Giả sử socola dạng thanh và rất đắng nên mỗi lần Nam chỉ ăn một nửa cái. Nếu lấy ra một thanh nguyên vẹn thì Nam bẻ đôi thanh socola đó rồi ăn một nửa, một nửa còn lại bỏ vào trong hộp. Nếu lấy ra là một nửa thanh thì Nam sẽ ăn ngay.

Giả sử nếu lấy ra một thanh nguyên vẹn thì Nam viết ra chữ D (devide), còn nếu lấy ra một nửa thì Nam viết chữ C (conquer). Hỏi Nam có tất cả bao nhiêu cách để ăn hết hộp có N thanh socola. Tức là có bao nhiêu xâu ký tự khác nhau được tạo ra.

**Input**

Dòng đầu ghi số bộ test, mỗi test ghi một số nguyên N là số thanh socola trong hộp (không quá 30).

**Ouput**

Mỗi test ghi ra số cách khác nhau giúp Nam ăn hết hộp socola đó.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 6  6  1  4  2  3  30 | 132  1  14  2  5  3814986502092304 |

### S51 - TỔNG DÃY CON LIÊN TIẾP

Cho dãy số nguyên dương A\[\] có N phần tử. Người ta cố gắng chia dãy A\[\] thành các đoạn liên tiếp sao tổng của các đoạn đó bằng nhau.

Ví dụ: dãy A\[\] = {2, 5, 1, 3, 3, 7} có thể được chia thành 3 đoạn {2, 5} {1, 3, 3} {7} cùng có tổng các phần tử bằng 7.

Hãy tính giá trị tổng liên tiếp **nhỏ nhất** có thể của các đoạn con tổng bằng nhau trong dãy A.

**Input**

Dòng đầu ghi số bộ test, không quá 1000.

Mỗi bộ test có hai dòng, dòng đầu ghi số N (1 &lt;= N &lt;= 105), các dòng tiếp theo, mỗi dòng ghi tối đa 10 số của dãy A\[\], các giá trị A\[i\] đều dương và không quá 20000.

**Output**

Ghi ra giá trị tổng nhỏ nhất tính được

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  6  2 5 1 3 3 7  6  1 2 3 4 5 6  20  1 1 2 1 1 2 1 1 2 1  1 2 1 1 2 1 1 2 1 1 | 7  21  2 |

### S53 - DÃY CON DÀI NHẤT

Cho hai dãy số thực A\[\] và B\[\] đều có N phần tử, các giá trị là số thực và không quá 100.

Hãy tính độ dài dài nhất của dãy các vị trí (không cần liên tiếp) thỏa mãn cả hai điều kiện:

- Nếu xét các vị trí đó trên dãy A\[\] thì dãy con thu được thỏa mãn tính chất tăng dần (giá trị bằng nhau không được tính vào dãy tăng).
- Nếu xét các vị trí đó trên dãy B\[\] thì dãy con thu được thỏa mãn tính chất giảm dần (giá trị bằng nhau không được tính vào dãy giảm).
 
**Input**

Dòng đầu ghi số bộ test (không quá 100).

Mỗi bộ test bắt đầu bởi số N (không quá 500).

Tiếp theo là N dòng, mỗi dòng ghi 2 giá trị A\[i\] và B\[i\]

**Output**

Với mỗi test, ghi ra độ dài tính được trên một dòng.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  2  1.0 1.0  1.5 0.0  3  1.0 1.0  1.0 1.0  1.0 1.0  6  1.5 9.0  2.0 2.0  2.5 6.0  3.0 5.0  4.0 2.0  10.0 5.5 | 2  1  4 |

### S61 - SỐ BƯỚC ÍT NHẤT

Cho mảng A\[\] gồm N số nguyên. Nhiệm vụ của bạn là sắp xếp lại mảng số với số lượng bước là ít nhất. Tại mỗi bước, bạn chỉ được phép chèn phần tử bất kỳ của mảng vào vị trí bất kỳ trong mảng. Ví dụ A\[\] = {2, 3, 5, 1, 4, 7, 6 }sẽ cho ta số phép chèn ít nhất là 3 bằng cách lấy số 1 chèn trước số 2, lấy số 4 chèn trước số 5, lấy số 6 chèn trước số 7 ta nhận được mảng được sắp.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là một số N; dòng tiếp theo đưa vào N số của mảng A\[\]; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤1000; 1≤A\[i\] ≤1000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1    7    2 3 5 1 4 7 6 | 3 |

### S63 - TỔNG CÁC XÂU CON

Cho số nguyên dương N được biểu diễn như một xâu ký tự số. Nhiệm vụ của bạn là tìm tổng của tất cả các số tạo bởi các xâu con của N. Ví dụ N=”1234” ta có kết quả là 1670 = 1 + 2 + 3 + 4 + 12 + 23 + 34 + 123 + 234 + 1234.

**Input:** Dòng đầu tiên đưa vào số lượng bộ test T. Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một số N. T, N thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤1012.

**Output:** Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    1234    421 | 1670    491 |

### S64 - SỐ NGUYÊN LỚN

Cho hai số nguyên lớn N và M có không quá 1000 chữ số. Người ta muốn tính xem liệu có thể lấy ra **nhiều nhất bao nhiêu chữ số** trong N, không cần liên tiếp nhau nhưng phải giữ nguyên thứ tự ban đầu để tạo ra một số X sao cho ta cũng có thể tìm thấy X trong số M theo cách tương tự.

**Input:** Dòng đầu tiên là số lượng bộ test T (T ≤ 20). Mỗi test gồm hai dòng, dòng thứ nhất ghi số N, dòng thứ 2 ghi số M.

**Output:** Với mỗi test, hãy in ra số chữ số nhiều nhất có thể của X.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  144615  4976135  44  88 | 4  0 |

*Giải thích test 1: số X tìm được là 4615.*

### S65 - SỐ THUẬN NGHỊCH

Cho số nguyên dương N có không quá 1000 chữ số.

Hãy tính độ dài lớn nhất của một số thuận nghịch tạo được bằng cách lấy liên tiếp các chữ số trong N.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 10).
- Mỗi test ghi ra một số nguyên dương N không quá 1000 chữ số.
 
**Output:** Với mỗi test, in ra đáp án tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  13731456  44444 | 5  5 |

 *Giải thích ví dụ:*

- *Test 1: số thuận nghịch dài nhất tìm được là 13731*
- *Test 2: số thuận nghịch dài nhất tìm được là 44444*

### S66 - XÂU ĐỐI XỨNG

Cho xâu ký tự S. Nhiệm vụ của bạn là tìm số phép chèn tối thiểu các ký tự vào S để S trở thành xâu đối xứng. Ví dụ: S = “ab” ta có số phép chèn tối thiểu là 1 để trở thành xâu đối xứng “aba” hoặc “bab”. Với xâu S = “aa” thì số phép chèn tối thiểu là 0. Với xâu S = “abcd” có số phép chèn tối thiểu là 3 để trở thành xâu “dcbabcd”

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một xâu ký tự được viết trên một dòng
- T, str thỏa mãn ràng buộc: 1≤T≤100; 1≤length(str)≤40.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    abcd    aba | 3    0 |

### S67 - KÝ TỰ GIỐNG NHAU

Giả sử bạn cần viết N ký tự giống nhau lên màn hình. Bạn chỉ được phép thực hiện ba thao tác dưới đây với chi phí thời gian khác nhau:

- Thao tác insert: chèn một ký tự với thời gian là X.
- Thao tác delete: loại bỏ ký tự cuối cùng với thời gian là Y.
- Thao tác copying: copy và paste tất cả các ký tự đã viết để số ký tự được nhân đôi với thời gian là Z.
 
Hãy tìm thời gian ít nhất để có thể đưa ra màn hình N ký tự giống nhau. Ví dụ với N = 9, X =1, Y = 2, Z =1 ta có kết quả là 5 bằng cách thực hiện: insert, insert, copying, copying, insert.

**Input:** Dòng đầu tiên đưa vào số lượng bộ test T. Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào N là số các ký tự giống nhau cần viết lên màn hình; dòng tiếp theo đưa vào bộ ba số X, Y, Z tương ứng với thời gian thực hiện ba thao tác; các số được viết cách nhau một vài khoảng trống. T, N, X, Y, Z thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤100; 1≤X, Y, Z ≤100.

**Output:** Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    9    1 2 1    10    2 5 4 | 5    14 |

### S70 - DÃY CON LIÊN TIẾP CÓ TỔNG BẰNG K

Cho dãy số A\[\] gồm có N phần tử không âm và số K.

Nhiệm vụ của bạn là hãy xác định xem có tìm được 1 dãy con liên tiếp mà tổng các phần tử bằng K hay không?

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test gồm số nguyên N và K (1≤ N ≤ 100 000, 0 ≤ K ≤ 1018).
- Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 109).
 
**Output:**

- Với mỗi test, in ra trên một dòng là đáp án thu được. Nếu có hãy in ra “YES”. Nếu không tìm được đáp án, in ra “NO”.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 3  6 33  1 4 20 3 10 5  7 7  1 4 0 0 3 10 5  2 0  1 4 | YES  YES  NO |

**Giải thích test 1:** 20+3+10 = 33

### S71 - TỔNG SỐ CÁCH DI CHUYỂN

Khu vui chơi trẻ em thiết kế một cầu thang có N bậc để di chuyển lên đỉnh tháp. Sinh viên PTIT cũng được phép leo lên cầu thang này nhưng nhìn chung chân sinh viên PTIT khá là dài nên có thể đi từ 1 đến K bậc mỗi bước (chứ không chỉ là 1 bậc như trẻ em).

Hãy tính xem sinh viên PTIT có bao nhiêu cách để leo lên đến đỉnh.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 100).
- Mỗi test gồm hai số nguyên dương N và K (1 ≤ N ≤ 100000, 1 ≤ K ≤ 100).
 
**Output:**

- Với mỗi test, in ra đáp án tìm được trên một dòng theo modulo 109+7.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  2 2  4 2 | 2  5 |

Giải thích test 2: Có 5 cách lần lượt là: (1, 1, 1, 1), (1, 1, 2), (1, 2, 1), (2, 1, 1), (2, 2).

### S72 - DÃY TAM GIÁC DÀI NHẤT

Cho dãy số A\[\] gồm có N phần tử. Một dãy con liên tiếp được gọi là dãy tam giác nếu như dãy đó tăng dần rồi lại giảm dần, hay tồn tại i, j, k sao cho A\[i\] ≤ A\[i+1\] ≤ … ≤ A\[k\] ≥ A\[k+1\] ≥ … ≥ A\[j\].

Nhiệm vụ của bạn là hãy tìm dãy con liên tiếp là dãy tam giác có độ dài lớn nhất.

Lưu ý: Dãy đơn điệu không giảm hoặc không tăng cũng là dãy tam giác. Ví dụ A\[\] = {10, 20, 30, 40} là một dãy tam giác.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm số nguyên N(1≤ N ≤ 100 000).

Dòng tiếp theo gồm N số nguyên A\[i\] (0 ≤ A\[i\] ≤ 106).

**Output:**

Với mỗi test, in ra trên một dòng là độ dài của dãy con tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  6  12 4 78 90 45 23  8  20 4 1 2 3 4 2 10 | 5  5 |

***Giải thích test 1:***

*Dãy tìm được là 4, 78, 90, 45, 23*

### S73 - ĐẦU TƯ BITCOIN

Xu hướng đầu tư bitcoin kiếm lời đang lan rộng. Thay vì hướng dẫn cách chơi, Học viện Hoàng Gia lại ra đề bài để thử thách khả năng tính toán tối ưu của sinh viên.

Biết trước giá bitcoin trong N ngày, và giả sử đang có 1 coin. Hãy tính toán lợi nhuận lớn nhất có thể thu được nếu bán đồng coin đó vào một ngày nào đó, sau đó mua lại chính đồng coin đó trong một ngày nào đó sau đó.

Chú ý: không được vừa mua vừa bán trong 1 ngày. Và chỉ mua bán một lần duy nhất.

**Input**

Dòng 1 ghi số N (*1 ≤ N ≤ 100000*)

Dòng tiếp theo ghi N số nguyên dương lần lượt là giá của đồng bitcoin trong N ngày (các giá trị không quá 100).

**Output**

Ghi ra giá trị lợi nhuận lớn nhất.

Hoặc nếu không thể có lợi nhuận thì ghi ra **“Lo nang roi!”**

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  1 3 2 | 1 |

### S75 - BỘ BA SỐ PYTAGO (BẢN KHÓ)

3 số a, b, c được gọi là một bộ số Pytago nếu như a2 + b2 = c2.

Cho số nguyên N, nhiệm vụ của bạn là hãy đếm bộ số (a, b, c) thỏa mãn 1 ≤a, b, c≤ N-1, a ≤b và a2 + b2 = c2 (mod N).

**Input:**

Một số nguyên dương N (2 ≤ N ≤ 500 000).

**Output:**

In ra một số nguyên là số bộ 3 số tìm được.

**Ví dụ:**

 | **Test 1** | **Test 2** |
|---|---|
| Input:  7  Output:  18 | Input:  15  Output:  64 |

### T301 - XÂU CON CHUNG DÀI NHẤT

Cho 2 xâu S1 và S2. Hãy tìm xâu con chung dài nhất của 2 xâu này *(các phần tử không nhất thiết phải liên tiếp nhau).*

**Input:** Dòng đầu tiên là số lượng bộ test T (T ≤ 20). Mỗi test gồm hai dòng, mô tả xâu S1 và S2, mỗi xâu có độ dài không quá 1000 và chỉ gồm các chữ cái in hoa.

**Output:** Với mỗi test, in ra độ dài dãy con chung dài nhất trên một dòng.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  AGGTAB  GXTXAYB  AA  BB | 4  0 |

Giải thích test 1: Dãy con chung là G, T, A, B.

### T304 - DÃY CON TĂNG DÀI NHẤT

Cho một dãy số nguyên gồm N phần tử A\[1\], A\[2\], ... A\[N\].

Biết rằng dãy con tăng là 1 dãy A\[i1\],... A\[ik\]

thỏa mãn i1 &lt; i2 &lt; ... &lt; ik và A\[i1\] &lt; A\[i2\] &lt; .. &lt; A\[ik\].

Hãy cho biết dãy con tăng dài nhất của dãy này có bao nhiêu phần tử?

**Input:** Dòng 1 gồm 1 số nguyên là số N (1 ≤ N ≤ 1000). Dòng thứ 2 ghi N số nguyên A\[1\], A\[2\], .. A\[N\] (1 ≤ A\[i\] ≤ 1000).

**Output:** Ghi ra độ dài của dãy con tăng dài nhất.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 6  1 2 5 4 6 2 | 4 |

### T305 - TỔNG LỚN NHẤT CỦA DÃY CON TĂNG DẦN

Cho dãy số A\[\] gồm N số. Nhiệm vụ của bạn là tìm tổng lớn nhất của dãy con được sắp theo thứ tự tăng dần của dãy A\[\]. Ví dụ với dãy A\[\] = {1, 101, 2, 3, 100, 4, 5} ta có kết quả là 106 = 1 + 2 + 3 + 100. Với dãy A\[\] = {10, 7, 5} ta có kết quả là 10. Với dãy A\[\] = {1, 2, 3, 5} ta có kết quả là 11.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng đầu tiên đưa vào N là số phần tử của dãy A\[\]; dòng tiếp theo đưa vào N số A\[i\]; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤103; 0≤A\[i\] ≤103.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  7  1 101 2 3 100 4 5  3  10 7 5  4  1 2 3 5 | 106  10  11 |

### T307 - CON ẾCH

Một con ếch có thể nhảy 1, 2, 3 bước để có thể lên đến một đỉnh cần đến. Hãy đếm số các cách con ếch có thể nhảy đến đỉnh.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là số n là số bước con ếch có thể lên được đỉnh.
- T, n thỏa mãn ràng buộc: 1≤T≤100; 1≤n ≤50.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | Input | Output |
|---|---|
| 2    1    5 | 1    13 |

### T308 - TỔ HỢP C(N, K)

Cho 2 số nguyên n, k. Bạn hãy tính C(n, k) modulo 109+7.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test gồm 2 số nguyên n, k (1 ≤ k ≤ n ≤ 1000).
 
**Output:**

- Với mỗi test, in ra đáp án trên một dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5 2  10 3 | 10  120 |

### T309 - BẬC THANG

Một chiếc cầu thang có N bậc. Mỗi bước, bạn được phép bước lên trên tối đa K bước. Hỏi có tất cả bao nhiêu cách bước để đi hết cầu thang? (Tổng số bước đúng bằng N).

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 100).
- Mỗi test gồm hai số nguyên dương N và K(1 ≤ N ≤ 100000, 1 ≤ K ≤ 100).
 
**Output:**

- Với mỗi test, in ra đáp án tìm được trên một dòng theo modulo 109+7.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  2 2  4 2 | 2  5 |

Giải thích test 1: Có 2 cách đó là (1, 1) và (2).

Giải thích test 2: 5 cách đó là: (1, 1, 1, 1), (1, 1, 2), (1, 2, 1), (2, 1, 1), (2, 2).

### TN01021 - TỔNG SỐ CÁCH DI CHUYỂN

Khu vui chơi trẻ em thiết kế một cầu thang có N bậc để di chuyển lên đỉnh tháp. Sinh viên PTIT cũng được phép leo lên cầu thang này nhưng nhìn chung chân sinh viên PTIT khá là dài nên có thể đi từ 1 đến K bậc mỗi bước (chứ không chỉ là 1 bậc như trẻ em).

Hãy tính xem sinh viên PTIT có bao nhiêu cách để leo lên đến đỉnh.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 100).
- Mỗi test gồm hai số nguyên dương N và K (1 ≤ N ≤ 100000, 1 ≤ K ≤ 100).
 
**Output:**

- Với mỗi test, in ra đáp án tìm được trên một dòng theo modulo 109+7.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  2 2  4 2 | 2  5 |

Giải thích test 2: Có 5 cách lần lượt là: (1, 1, 1, 1), (1, 1, 2), (1, 2, 1), (2, 1, 1), (2, 2).

## NGĂN XẾP - HÀNG ĐỢI

### 1514 - SỬA LẠI DÃY NGOẶC

Cho một xâu chỉ gồm các kí tự ‘(‘, ‘) và có độ dài chẵn. Hãy đếm số lượng dấu ngoặc cần phải đổi chiều ít nhất, sao cho xâu mới thu được là một dãy ngoặc đúng.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 20).

Mỗi test gồm 1 xâu S có độ dài không vượt quá 100 000, chỉ gồm dấu ( và ).

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

**Ví dụ:**

| Input: | Output |
|---|---|
| 4  ))((  ((((  (((())  )(())((( | 2  2  1  3 |

### 1515 - BIỂU THỨC TƯƠNG ĐƯƠNG

Cho biểu thức đúng P chỉ bao gồm các phép toán +, -, các toán hạng cùng với các ký tự ‘(’, ‘)’. Hãy bỏ tất cả các ký tự ‘(’, ‘)’ trong P để nhận được biểu thức tương đương. Ví dụ với P = a – (b + c) ta có kết quả P = a – b – c .

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T;
- Những dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một biểu thức P được viết trên một dòng.

**Output**:

- Đưa ra kết quả mỗi test theo từng dòng.

**Ràng buộc**:

- T, P thỏa mãn ràng buộc: 1≤T≤100; 1≤length(P)≤103.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    a–(b+c)    a-(b-c-(d+e))-f | a-b-c    a-b+c+d+e-f |

### 1516 - SO SÁNH BIỂU THỨC

Cho P1, P2 là hai biểu thức đúng chỉ bao gồm các ký tự mở ngoặc ‘(’ hoặc đóng ngoặc ‘)’ và các toán hạng in thường. Nhiệm vụ của bạn là định xem P1 và P2 có giống nhau hay không.

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T;
- Những dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất đưa vào P1, dòng tiếp theo đưa vào P2.

**Output**:

- Đưa ra kết quả mỗi test theo từng dòng.

**Ràng buộc**:

- T, P thỏa mãn ràng buộc: 1≤T≤100; 1≤length(P) ≤100.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    -(a+b+c)    -a-b-c    a-b-(c-d)    a-b-c-d | YES    NO |

### 1518 - TÍNH GIÁ TRỊ BIỂU THỨC HẬU TỐ

Hãy viết chương trình chuyển tính toán giá trị của biểu thức hậu tố.

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T;
- Những dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một biểu thức hậu tố exp. Các số xuất hiện trong biểu thức là các số đơn có 1 chữ số.

**Output**:

- Đưa ra kết quả mỗi test theo từng dòng, chỉ lấy giá trị phần nguyên.

**Ràng buộc**:

- T, exp thỏa mãn ràng buộc: 1≤T≤100; 2≤length(exp)≤20.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2  231\*+9–  875\*+9- | -4  34 |

### 1519 - TÍNH GIÁ TRỊ BIỂU THỨC TIỀN TỐ

 Hãy viết chương trình tính toán giá trị của biểu thức tiền tố.

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T;
- Những dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một biểu thức tiền tố exp. Các số xuất hiện trong biểu thức là các số đơn có 1 chữ số.

**Output**:

- Đưa ra kết quả mỗi test theo từng dòng, chỉ lấy giá trị phần nguyên.

**Ràng buộc**:

- T, exp thỏa mãn ràng buộc: 1≤T≤100; 2≤length(exp)≤20.

**Ví dụ:**

| Input | Output |
|---|---|
| 2  -+8/632  -+7\*45+20 | 8  25 |

### 1521 - GIẢI MÃ XÂU KÝ TỰ

Cho xâu ký tự mã hóa str. Hãy viết chương trình giải mã xâu ký tự str. Xâu ký tự mã hóa được thực hiện theo số lần lặp các xâu con của str như sau:

Xâu đầu vào: “abbbababbbababbbab ”

Xâu mã hóa : "3\[a3\[b\]1\[ab\]\]"

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T;
- Những dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một xâu mã hóa str được viết trên một dòng.

**Output**:

- Đưa ra kết quả mỗi test theo từng dòng.

**Ràng buộc**:

- T, str thỏa mãn ràng buộc: 1≤T≤100; 1≤length(str)≤100.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2    1\[b\]    3\[b2\[ca\]\] | b    bcacabcacabcaca |

### 1524 - GIÁ TRỊ NHỎ NHẤT CỦA XÂU

Cho xâu ký tự S\[\] bao gồm các ký tự in hoa \[A, B, …,Z\]. Ta định nghĩa giá trị của xâu S\[\] là tổng bình phương số lần xuất hiện mỗi ký tự trong xâu. Ví dụ với xâu S\[\] = “AAABBCD” ta có F(S) = 32 + 22 + 12 + 12 = 15. Hãy tìm giá trị nhỏ nhất của xâu S\[\] sau khi loại bỏ K ký tự trong xâu.

**Input**:

- Dòng đầu tiên đưa vào số lượng test T (T≤100).
- Mỗi test được tổ chức thành 2 dòng. Dòng thứ nhất ghi lại số K. Dòng thứ 2 ghi lại xâu ký tự S\[\] có độ dài không vượt quá 10^6.

Output:

- Đưa ra giá trị nhỏ nhất của mỗi test theo từng dòng.

| Input | Output |
|---|---|
| 2  0  ABCC  1  ABCC | 6  3 |

### 1525 - SỐ BDN

Ta gọi số nguyên dương K là một số BDN nếu các chữ số trong K chỉ bao gồm các 0 hoặc 1 có nghĩa. Ví dụ số K = 101 là số BDN, k=102 không phải là số BDN.

Số BDN của N là số P =M´N sao cho P là số BDN. Cho số tự nhiên N (N&lt;1000), hãy tìm số BDN nhỏ nhất của N.

**Ví dụ**. Với N=2, ta tìm được số BDN của N là P = 5´2=10. N = 17 ta tìm được số BDN của 17 là P = 653´17=11101.

**Input:**

- Dòng đầu tiên ghi lại số tự nhiên T là số lượng Test;
- T dòng kế tiếp mỗi dòng ghi lại một bộ Test. Mỗi test là một số tự nhiên N.

 **Output:**

 Đưa ra kết quả mỗi test theo từng dòng.

 **Ví dụ:**

| **Input** | **Output** |
|---|---|
| 3  2  12  17 | 10  11100  11101 |

## NGĂN XẾP VÀ HÀNG ĐỢI

### 1517 - BÀI 4. BIẾN ĐỔI TRUNG TỐ - HẬU TỐ

Hãy viết chương trình chuyển đổi biểu thức biểu diễn dưới dạng trung tố về dạng hậu tố.

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T;
- Những dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một biểu thức tiền tố exp.

**Output**:

- Đưa ra kết quả mỗi test theo từng dòng.

**Ràng buộc**:

- T, exp thỏa mãn ràng buộc: 1≤T≤100; 2≤length(exp)≤10.

**Ví dụ:**

| Input | Output |
|---|---|
| 2  (A+(B+C)  ((A\*B)+C) | ABC++  AB\*C+ |

### 1520 - BÀI 7. TÍNH TOÁN GIÁ TRỊ BIỂU THỨC TRUNG TỐ

Cho biểu thức trung tố S với các toán tử +, -, \*, / và dấu ngoặc (). Các toán hạng là các số có giá trị không vượt quá 100. Hãy tính giá trị biểu thức S. Phép chia thực hiện với số nguyên, input đảm bảo số bị chia luôn khác 0, đáp số biểu thức có không quá 10 chữ số.

**Input:**

Dòng đầu tiên là số lượng bộ test (T ≤ 100).

Mỗi dòng gồm một xâu S, không quá 100 kí tự. Các toán hạng là các số nguyên không âm.

**Output:**

Với mỗi test, in ra đáp án tìm được.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 4  6\*3+2-(6-4/2)  100+99\*22  6\*((4\*3)+5)  1-2 | 16  2278  102  -1 |

### 1526 - BÀI 13. KHOẢNG CÁCH XÂU KÝ TỰ

Cho tập n xâu ký tự S và hai xâu s, t Î S. Ta giả thiết các xâu ký tự S\[i\] Î S có độ dài bằng nhau. Hãy tìm khoảng cách đường đi ngắn nhất từ s đến t. Biết từ một xâu ký tự bất kỳ ta chỉ được phép dịch chuyển đến xâu khác với nó duy nhất 1 ký tự. Ví dụ ta có tập các từ S = { POON, TOON, PLEE, SAME, POIE, PLEA, PLIE, POIN }, s = TOON, t = PLEA ta có độ dài đường đi ngắn nhất là 7 tương ứng với các phép dịch chuyển : TOON -&gt; POON –&gt; POIN –&gt; POIE –&gt; PLIE –&gt; PLEE –&gt; PLEA.

**Input:**

- Dòng đầu tiên đưa vào số lượng test T (T≤100).
- Mỗi test được tổ chức thành 2 dòng. Dòng thứ nhất ghi lại n là số từ trong S và hai từ s, t. Dòng thứ 2 đưa vào n xâu xâu ký tự của S; các xâu ký tự được viết cách nhau một vài khoảng trống, có độ dài không vượt quá 10 kí tự.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 1  8 TOON PLEA  POON TOON PLEE SAME POIE PLEA PLIE POIN | 7 |

### 1527 - BÀI 14. TÌM SỐ K THỎA MÃN ĐIỀU KIỆN

Cho hai số nguyên dương L, R. Hãy đưa ra số các số K trong khoảng \[L, R\] thỏa mãn điều kiện:

- Tất cả các chữ số của K đều khác nhau.
- Tất cả các chữ số của K đều nhỏ hơn hoặc bằng 5.

Ví dụ với L = 4, R = 13 ta có 5 số thỏa mãn yêu cầu là 4, 5, 10, 12, 13,

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Dòng tiếp theo đưa vào các bộ test. Mỗi bộ test được là một cặp L, R được viết trên một dòng.
- T, L, R thỏa mãn ràng buộc: 1≤T≤100; 0≤L≤R≤105.

**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 2  4 13  100 1000 | 5  100 |

### 1528 - BÀI 15. QUAY HÌNH VUÔNG

Có một chiếc bảng hình chữ nhật với 6 miếng ghép, trên mỗi miếng ghép được điền một số nguyên trong khoảng từ 1 đến 6. Tại mỗi bước, chọn một hình vuông (bên trái hoặc bên phải), rồi quay theo chiều kim đồng hồ.

|  |  |  |
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

### 1529 - BÀI 16. DI CHUYỂN TRÁNH VẬT CẢN

Cho một bảng kích thước N x N, trong đó có các ô trống ‘.’ và vật cản ‘X’. Các hàng và các cột được đánh số từ 0.

Mỗi bước di chuyển, bạn có thể đi từ ô (x, y) tới ô (u, v) nếu như 2 ô này nằm trên cùng một hàng hoặc một cột, và không có vật cản nào ở giữa.

Cho điểm xuất phát và điểm đích. Bạn hãy tính số bước di chuyển ít nhất?

**Input:**

- Dòng đầu ghi số bộ test (không quá 10). Mỗi test gồm: 
    - Dòng đầu tiên là số nguyên dương N (1 ≤ N ≤ 100).
    - N dòng tiếp theo, mỗi dòng gồm N kí tự mô tả bảng.
    - Cuối cùng là 4 số nguyên a, b, c, d với (a, b) là tọa độ điểm xuất phát, (c, d) là tọa độ đích. Dữ liệu đảm bảo hai vị trí này không phải là ô có vật cản.

**Output:**

- Với mỗi test, in ra một số nguyên là đáp số của bài toán.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 1  3  .X.  .X.  ...  0 0 0 2 | 3 |

### 1530 - BÀI 17.  HEXGAME

HEXGAME là một trò chơi xếp hình gồm 10 miếng ghép hình lục giác đều, trên mỗi miếng ghép được điền một số nguyên, có 8 miếng được điền số từ 1 đến 8 và có hai miếng điền số 0. Các miếng liên kết với nhau tạo thành lưới tổ ong. Ban đầu các miếng ghép ở vị trí như hình vẽ. Tại mỗi bước, chọn một miếng ghép có đúng 6 miếng ghép kề cạnh làm tâm, rồi xoay một nấc 6 miếng ghép kề cạnh đó theo chiều kim đồng hồ. Như vậy chỉ có hai cách chọn tâm, đó là chọn tâm bên trái và chọn tâm bên phải.

Yêu cầu: Cho một trạng thái của trò chơi (nhận được sau một dãy biến đổi từ trạng thái ban đầu), hãy tính số phép biến đổi ít nhất để đưa về trạng thái ban đầu.

**Input:**

- Dòng đầu ghi số bộ test (không quá 10). Mỗi bộ test gồm: 
    - Dòng đầu tiên chứa 3 số ở 3 miếng ghép dòng thứ nhất (thứ tự từ trái qua phải).
    - Dòng thứ hai chứa 4 số ở 4 miếng ghép dòng thứ hai (thứ tự từ trái qua phải).
    - Dòng thứ 3 chứa 3 số ở 3 miếng ghép dòng thứ ba (thứ tự từ trái qua phải).

**Output:**

- Với mỗi bộ test in ra một số nguyên là số phép biến đổi ít nhất để đưa được về trạng thái ban đầu.

**Ví dụ:**

| **Input** | **Output** |
|---|---|
| 1  1 0 2  8 6 0 3  7 5 4 | 5 |

### 1531 - BÀI 18. TÍNH TỔNG

Cho một xâu s. Với mỗi một xâu con X liên tiếp của s có độ dài bằng K, giá trị đặc biệt của nó được tính bằng giá trị của X trong hệ cơ số B modulo M.

Nhiệm vụ của bạn là tính tổng giá trị đặc biệt của tất cả các xâu con của s có độ dài bằng K.

**Input:**

Dòng đầu tiên gồm xâu S có độ dài không quá 300 000 gồm các kí tự từ 0 – 9.

Dòng tiếp theo là số nguyên K, B và M (1 &lt;= K &lt;= |s|, 2 &lt;= B &lt;= 10, 1 &lt;= M &lt;= 1000).

**Output:**

In ra đáp án tìm được.

**Test ví dụ:**

| Test 1 | Test 2 |
|---|---|
| Input:  12212  3 3 5  Output:  5 | Input:  111101  4 2 15  Output:  27 |

Giải thích test 1:

Giá trị của xâu con 122 trong cơ số 3 bằng 17 % 5 = 2.

Giá trị của xâu con 221 trong cơ số 3 bằng 25 % 5 = 0.

Giá trị của xâu con 212 trong cơ số 3 bằng 23 % 5 = 3.

Tổng của chúng bằng 5.

### 1532 - BÀI 19. BỘI SỐ LỚN NHẤT CỦA 3

Cho dãy số A\[\] có N phần tử là các chữ số từ 0 đến 9. Nhiệm vụ của bạn là hãy chọn lấy một tổ hợp các phần tử và sắp xếp chúng sao cho thu được số lớn nhất chia hết cho 3.

Nếu không tìm được số nào, in ra -1.

**Input:**

Dòng đầu tiên là số lượng bộ test T (1 &lt;= N &lt;= 50).

Mỗi test bắt đầu bởi số nguyên N (1 &lt;= N &lt;= 100 000).

Dòng tiếp theo gồm N số nguyên A\[i\] (0 &lt;= A\[i\] &lt;= 9).

**Output:**

Với mỗi test, in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 3  3  8 1 9  5  8 1 7 6 0  2  5 2 | 981  8760  -1 |

### S211 - BIỂU THỨC TĂNG GIẢM

Cho dãy ký tự S chỉ bao gồm các ký tự I hoặc D. Ký tự I được hiểu là tăng (Increasing) ký tự D được hiểu là giảm (Decreasing). Sử dụng các số từ 1 đến 9, hãy đưa ra số nhỏ nhất được đoán nhận từ S. Chú ý, các số không được phép lặp lại. Dưới đây là một số ví dụ mẫu:

- A\[\] = “I” : số tăng nhỏ nhất là 12.
- A\[\] = “D” : số giảm nhỏ nhất là 21
- A\[\] =”DD” : số giảm nhỏ nhất là 321
- A\[\] = “DDIDDIID”: số thỏa mãn 321654798
 
**Input:** Dòng đầu tiên đưa vào số lượng bộ test T. Những dòng kế tiếp đưa vào T bộ test. Mỗi bộ test là một xâu S. T, S thỏa mãn ràng buộc: 1≤ T ≤100; 1≤ length(S) ≤8; .

**Output:** Đưa ra thứ tự bộ test và kết quả mỗi test theo từng dòng.

**Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 4  I  D  DD    DDIDDIID | Test 1: 12  Test 2: 21  Test 3: 321  Test 4: 321654798 |

### S218 - LOẠI BỎ DẤU NGOẶC

Cho một biểu thức đúng và thỏa mãn:

\- Các biến trong biểu thức chỉ chứa các chữ cái viết hoa.

\- Các toán tử trong biểu thức là ‘+’ hoặc ‘-’

Hãy loại bỏ các dấu ngoặc thừa mà vẫn giữ nguyên ý nghĩa của biểu thức.

**Input:**

\- Dòng đầu tiên chứa số biểu thức M (1&lt;=M&lt;=10).

\- M dòng tiếp theo, mỗi dòng là một biểu thức đúng, có thể có các dấu cách tùy ý trong mỗi dòng. Độ dài mỗi dòng (bao gồm cả dấu cách) không quá 255 kí tự.

**Output:**

Với mỗi biểu thức, in ra trên một dòng biểu thức không có các dấu ngoặc thừa.

Chú ý: Thứ tự của các toán hạng trong biểu thức kết quả và biểu thức đầu vào phải giống nhau. Các dấu cách thừa nếu có cũng phải được loại bỏ.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  (A - B + C)-(A+ (B–C)) - (C- (D- E) )  ((A)- ((B ) ))  A-( B+C) | A-B+C-(A+B-C)-(C-(D-E))  A-B  A-(B+C) |

### S228 - GIẤY KHAI SINH

Một buổi họp mặt đại gia đình nhân dịp cụ già Ted tròn 100 tuổi, người ta muốn sắp xếp con cháu của cụ theo thứ tự từ tuổi cao xuống thấp. Giả sử ta có thông tin về giấy khai sinh của từng người đó. Mỗi giấy khai sinh chỉ viết ba thông tin đơn giản gồm: *Tên người cha, Tên người con, Tuổi của người cha lúc sinh con*.

Hãy giúp đại gia đình trên tính ra tuổi của từng người con cháu cụ Ted và viết ra danh sách theo thứ tự từ tuổi cao xuống thấp.

**Input**

Dòng đầu ghi số bộ test (không quá 100). Với mỗi bộ test:

- Dòng đầu tiên ghi số X (0&lt;X&lt;100) là số người con cháu cần sắp xếp.
- Tiếp theo là X dòng, mỗi dòng ghi thông tin về một giấy khai sinh của từng người (thứ tự ngẫu nhiên) gồm 3 thành phần, mỗi thành phần cách nhau một khoảng trống:
    - Tên người cha: không quá 20 ký tự và không chứa khoảng trống
 
- - Tên người con: không quá 20 ký tự và không chứa khoảng trống
    - Tuổi của người cha khi sinh con: 1 số nguyên dương, không quá 100.
 
**Output**

- Với mỗi bộ test, in ra màn hình thứ tự bộ test (xem thêm trong bộ test ví dụ), sau đó lần lượt là từng người trong danh sách tuổi từ cao xuống thấp (không tính cụ Ted). Mỗi người viết ra hai thông tin: tên, một khoảng trống rồi đến tuổi của người đó.
- Nếu hai người có cùng tuổi thì xếp theo thứ tự từ điển.
 
**Ví dụ**

 | **INPUT** | **OUTPUT** |
|---|---|
| 2  1  Ted Bill 25  4  Ray James 40  James Beelzebub 17  Ray Mark 75  Ted Ray 20 | DATASET 1     Bill 75     DATASET 2     Ray 80     James 40     Beelzebub 23     Mark 5 |

## CÁC CẤU TRÚC DỮ LIỆU NÂNG CAO

### 1545 - GIÁ TRỊ LỚN NHẤT

Cho dãy số gồm N phần tử có giá trị ban đầu bằng 0.

Có M phép biến đổi, mỗi phép có dạng (u, v, k): tăng mỗi phần tử từ u tới v lên k đơn vị.

Cho Q câu hỏi, mỗi câu hỏi có dạng (u, v): yêu cầu tìm phần tử lớn nhất trong đoạn \[u, v\].

**Input**

- Dòng đầu tiên gồm 2 số nguyên N và M (1 &lt;= N, M &lt;= 100 000).
- M dòng tiếp theo, mỗi dòng gồm 3 số u, v, k (1 &lt;= k &lt;= 10 000).
- Dòng tiếp theo là số nguyên Q (1 &lt;= Q &lt;= 100 000).
- Q dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v.

**Output**

- Với mỗi truy vấn, hãy in ra đáp án trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 6 2  1 3 2  4 6 3  1  3 4 | 3 |

### 1546 - VẪN LÀ GIÁ TRỊ LỚN NHẤT

Cho dãy số gồm N phần tử có giá trị ban đầu bằng 0.

Có Q truy vấn:

Loại 1 có dạng (1, u, v, k): tăng mỗi phần tử từ u tới v lên k đơn vị (1 &lt;= k &lt;= 10 000).

Loại 2 có dạng (2, u, v): yêu cầu tìm phần tử lớn nhất trong đoạn \[u, v\].

**Input**

- Dòng đầu tiên gồm 2 số nguyên N và Q (1 &lt;= N, M &lt;= 100 000).
- Q dòng tiếp theo, mỗi dòng gồm một trong hai loại truy vấn như trên.

**Output**

- Với mỗi truy vấn loại 2, hãy in ra đáp án trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 6 3  1 1 3 3  1 4 6 4  2 1 6 | 4 |

### 1547 - DÃY CON NHỎ NHẤT CÓ USCLN BẰNG K

Cho dãy số A\[\] có N phần tử. Nhiệm vụ của bạn là tìm dãy con liên tiếp có độ dài nhỏ nhất, sao cho UCLN của các phần tử đúng bằng K.

**Input**

- Dòng đầu tiên là số lượng bộ test T (T &lt;= 10).
- Mỗi test bắt đầu bằng 2 số nguyên N và K (1 &lt;= N &lt;= 100 000).
- Dòng tiếp theo gồm N số nguyên A\[i\] (1 &lt;= A\[i\], K &lt;= 10^9).

**Output**

- Với mỗi test, hãy in ra đáp án trên một dòng. Nếu không tìm được dãy con nào, in ra -1.

**Test ví dụ:**

| Input | Output |
|---|---|
| 3  8 3  6 9 7 10 12 24 36 27  4 3  2 4 6 8  4 6  1 2 3 6 | 2  -1  1 |

### 1548 - PHẦN TỬ TRUNG VỊ

Phần tử trung vị của một dãy số có n phần tử là phần tử chính giữa (số thứ a\[(n+1)/2\]) sau khi dãy số được sắp xếp. Ví dụ dãy A\[\] = \[1, 2, 3, 4, 5\], phần tử trung vị là 3.

Cho một dãy số ban đầu rỗng và Q truy vấn, mỗi truy vấn có dạng:

- add x: Thêm số x vào dãy số (1 &lt;= x &lt;= 10^6).
- del x: Xóa bỏ x (x đảm bảo tồn tại trong dãy)
- print: Yêu cầu in ra phần tử trung vị của dãy số.

**Input**

- Dòng đầu tiên là số lượng truy vấn Q (Q &lt;= 100 000).
- Q dòng tiếp theo, mỗi dòng gồm một trong 3 loại truy vấn như trên.

**Output**

- Với mỗi truy vấn “print”, hãy in ra phần tử trung vị của dãy số.

**Test ví dụ:**

| Input | Output |
|---|---|
| 10  add 1  add 4  add 7  add 8  print  add 9  print  del 1  del 8  print | 4  7  7 |

Giải thích truy vấn 1: Dãy số hiện tại là \[1, 4, 7, 8\]. Phần tử trung vị là 4.

### 1549 - K-QUERY

Cho dãy số A\[\] có N phần tử. Có Q truy vấn dạng (u, v, K) yêu cầu bạn xác định số lượng phần tử lớn hơn K trong dãy con A\[u\], A\[u+1\], ..., A\[v\].

**Input**

- Dòng đầu tiên là số nguyên N (1 &lt;= N &lt;= 100 000).
- Dòng tiếp theo gồm N số nguyên A\[i\] (1 &lt;= A\[i\] &lt;= 10^9).
- Tiếp theo là số lượng truy vấn Q (1 &lt;= Q &lt;= 100 000).
- Q dòng tiếp theo, mỗi dòng gồm 3 số nguyên u, v, K (1 &lt;= u, v &lt;= N, 1 &lt;= K &lt;= 10^9).

**Output**

- Với mỗi truy vấn, in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 5  5 1 2 3 4  3  2 4 1  4 4 4  1 5 2 | 2  0  3 |

### 1550 - CHẠY ĐUA KỲ THÚ

Với một trang trại rộng lớn, nông dân Bell quyết định tổ chức của đua cho những con bò của mình để nâng cao thể lực. Hành trình của cuộc đua gồm có N trạm. Mỗi thí sinh có một hành trình khác nhau và phải tuân thủ chạy lần lượt theo thứ tự từ trạm xuất phát đến trạm đích.

Để tăng thêm sự thú vị cho cuộc thi, thỉnh thoảng anh Bell sẽ thay đổi vị trí của các trạm. Biết rằng các con bò của mình không đủ thể lực, anh Bell cho phép các thí sinh được bỏ qua một trạm nào đó trong hành trình của nó. Và anh vẫn thầm nghĩ rằng, chắc chúng chẳng chọn ra được giải pháp tối ưu đâu.

Các con bò của nông dân Bell không được thông minh cho lắm, các bạn hãy giúp chúng tính quãng đường ngắn nhất để hoàn thành chặng đua của mình.

Khoảng cách giữa 2 trạm có tọa độ (x1, y1) và (x2, y2) được tính bằng khoảng cách Manhattan theo công thức |x1-x2| + |y1-y2|.

**Input**

- Dòng đầu tiên gồm 2 số nguyên N và Q.
- N dòng tiếp theo, mỗi dòng cho biết tọa độ x\[i\], y\[i\] của trạm thứ i.
- Q dòng tiếp theo, mỗi dòng thuộc một trong hai dạng dưới đây: 
    - Truy vấn “U I X Y” làm thay đổi tọa độ điểm thứ I thành tọa độ mới (X, Y)
    - Truy vấn “Q I J” cho biết một thí sinh của anh Bell phải chạy từ trạm I tới trạm J. Bạn hãy tính thời gian ngắn nhất để thí sinh này hoàn thành cuộc thi.

**Output**

- Với mỗi truy vấn loại 2, hãy in ra đáp án trên một dòng.

**Giới hạn:**

- 1 &lt;= N, Q &lt;= 100 000.
- -1000 &lt;= x\[i\], y\[i\] &lt;= 1000.
- 30% test có N, Q &lt;= 1000.

**Test ví dụ:**

| Input | Output |
|---|---|
| 5 5  -4 4  -5 -3  -1 5  -3 4  0 5  Q 1 5  U 4 0 1  U 4 -1 1  Q 2 4  Q 1 4 | 11  8  8 |

**Giải thích test:**

Truy vấn 1: Bỏ qua trạm thứ 2, hành trình 1à3à4à5.

### 1551 - ĐẾM SỐ TAM GIÁC

Cho mặt phẳng Oxy, có Q truy vấn:

Loại 1 có dạng (1, x, y): thêm một điểm tại tọa độ (x, y). Các điểm thêm vào là phân biệt.

Loại 2 có dạng (2, a, b, u, v): yêu cầu số tam giác được tạo ra từ 3 điểm nằm trong hình chữ nhật có điểm trái dưới là (a, b), điểm phải trên là (u, v) (a &lt;= u, b &lt;= v).

**Input**

- Dòng đầu tiên là số nguyên Q (1 &lt;= Q &lt;= 100 000).
- Q dòng tiếp theo, mỗi dòng gồm một trong hai loại truy vấn như trên.
- Các tọa độ nằm trong khoảng từ 1 tới 1000.

**Output**

- Với mỗi truy vấn loại 2, hãy in ra đáp án trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 8  1 2 2  1 3 5  1 4 2  1 4 5  1 5 4  2 1 1 6 6  1 3 3  2 1 1 6 6 | 10  20 |

### 1552 - SỐ CẶP NGHỊCH THẾ TRONG MA TRẬN

Cho ma trận A có kích thước N x N. Nhiệm vụ của bạn là đếm số lượng cặp nghịch thế thỏa mãn: x1 &lt;= x2, y1 &lt;= y2 và A\[x2\]\[y2\] &lt; A\[x1\]\[y1\].

**Input**

- Dòng đầu tiên là số lượng bộ test T (T &lt;= 10).
- Mỗi test bắt đầu bởi số nguyên N (1 &lt;= N &lt;= 500).
- N dòng tiếp theo, mỗi dòng gồm N số nguyên mô tả ma trận A (1 &lt;= A\[i\]\[j\] &lt;= 10^9).

**Output**

- Với mỗi test, in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 2  2  7 5  3 1  4  4 7 2 9  6 4 1 7  5 3 8 1  3 2 5 6 | 5  43 |

### 1553 - SỐ NHỎ THỨ K

Cho dãy số A\[\] có N phần tử. Có Q truy vấn dạng (u, v, K) yêu cầu bạn tìm số nhỏ thứ K trong dãy con A\[u\], A\[u+1\], ..., A\[v\].

**Input**

- Dòng đầu tiên chứa 2 số N và Q (1 &lt;= N &lt;= 100 000, 1 &lt;= Q &lt;= 5000).
- Dòng tiếp chứa N số nguyên A\[i\] (-10^9 &lt;= A\[i\] &lt;= 10^9), các số là phân biệt.
- Q dòng tiếp, mỗi dòng gồm 3 số nguyên u, v, K (1 &lt;= K &lt;= v-u+1).

**Output**

- Với truy vấn, in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 7 3  1 5 2 6 3 7 4  2 5 3  4 4 1  1 7 3 | 5  6  3 |

### 1554 - TRUY VẤN TRÊN CÂY

Cho một cây có N đỉnh. Mỗi đỉnh có trọng số w\[i\]. Có M truy vấn, mỗi truy vấn có dạng (u, v, k) yêu cầu bạn tìm đỉnh có trọng số nhỏ thứ k trên đường đi từ u tới v.

**Input**

- Dòng đầu tiên chứa 2 số N và M (1 &lt;= N, M &lt;= 100 000).
- Dòng tiếp gồm N số nguyên w\[i\] (1 &lt;= w\[i\] &lt;= 10^9)
- N-1 dòng tiếp, mỗi dòng gồm 2 số nguyên u và v cho biết đỉnh u nối với đỉnh v.
- M câu truy vấn, mỗi dòng có dạng u v k (k đảm bảo nằm trong phạm vi độ dài đường đi từ u tới v).

**Output**

- Với truy vấn, in ra đáp án tìm được trên một dòng.

**Test ví dụ:**

| Input | Output |
|---|---|
| 8 5  105 2 9 3 8 5 7 7  1 2  1 3  1 4  3 5  3 6  3 7  4 8  2 5 1  2 5 2  2 5 3  2 5 4  7 8 2 | 2  8  9  105  7 |

## KIỂU DỮ LIỆU VÀ PHÉP TOÁN

### C01025 - HÌNH VUÔNG NHỎ NHẤT

Cho 2 hình chữ nhật trên mặt phẳng Oxy. Cần tìm hình vuông có kích thước nhỏ nhất sao cho phủ kín được 2 hình chữ nhật đã cho.

**Dữ liệu vào:**

2 dòng, mỗi dòng gồm 4 số nguyên lần lượt mô tả điểm trái dưới và phải trên của hình chữ nhật. Các tọa độ có giá trị tuyệt đối không vượt quá 100.

**Kết quả:**

In ra diện tích của hình vuông tìm được.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 6 6 8 8  1 8 4 9 | 49 |

## VÒNG LẶP

### C01052 - ƯỚC SỐ CHIA HẾT CHO 2

\# Cho số nguyên dương N. Nhiệm vụ của bạn là hãy xác định xem có bao nhiêu ước số của N chia hết cho 2? \*\*Input:\*\* Dòng đầu tiên là số lượng bộ test T (T ≤ 100). Mỗi bộ test gồm một số nguyên N (1 ≤ N ≤ 109) \*\*Output:\*\* Với mỗi test, in ra đáp án tìm được trên một dòng. \*\*Ví dụ:\*\*

| Input: | Output: |
|---|---|
| 2  9  8 | 0  3 |

### C03051 - SỐ CHỈ CÓ BA ƯỚC SỐ

Cho hai số L, R. Nhiệm vụ của bạn là hãy đếm tất cả các số có đúng ba ước số trong khoảng \[L, R\]. Ví dụ L =1, R =10, ta có kết quả là 2 vì chỉ có số 4 và 9 là có đúng 3 ước số.

**Input:**

- Dòng đầu tiên đưa vào số lượng test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là cặp số L, R.
- T, N thỏa mãn rang buộc 1≤T≤100; 1≤L, R ≤1012.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  1 10  1 1000000000000 | 2  78498 |

## VIẾT HÀM

### C03038 - ƯỚC SỐ CỦA GIAI THỪA

Cho số tự nhiên N và số nguyên tố P. Nhiệm vụ của bạn là tìm số x lớn nhất để N! chia hết cho px. Ví dụ với N=7, p=3 thì x=2 là số lớn nhất để 7! Chia hết cho 32.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là cặp số N, p được viết cách nhau một vài khoảng trống.
- T, N, p thỏa mãn ràng buộc : 1≤T≤100; 1≤N≤105; 2≤p≤5000;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 **Ví dụ:**

 | Input: | Output: |
|---|---|
| 3    62 7    76 2    3 5 | 9    73    0 |

### C03058 - BỘI SỐ NHỎ NHẤT CỦA N SỐ NGUYÊN DƯƠNG ĐẦU TIÊN

Cho số tự nhiên n. Nhiệm vụ của bạn là tìm số nguyên dương nhỏ nhất chia hết cho 1, 2, .., n.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- T dòng tiếp theo mỗi dòng đưa vào một bộ test. Mỗi bộ test là một số tự nhiên n.
- T thỏa mãn ràng buộc: 1≤T≤104; n không quá 100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
 Ví dụ:**

 | Input | Output |
|---|---|
| 2  3  5 | 6  60 |

### C03060 - CHIA HẾT

Cho hai số nguyên dương n và k. Hãy kiểm tra xem giai thừa của n (n!) có chia hết cho 2k hay không.

**Input**

Có một dòng ghi 2 số n và k (1 ≤ n, k ≤ 100).

**Output**

Nếu n! chia hết cho 2k thì in ra “Yes”, ngược lại in ra “No”.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 5 3 | Yes |
| **Input** | **Output** |
| 1 1 | No |

### CTEST022 - TÁCH ĐÔI

Cho số nguyên dương N không quá 18 chữ số. Nếu số chữ số của N là chẵn thì ta có thể tách thành hai nửa trái và phải có số chữ số bằng nhau.

Hãy tính bội số chung nhỏ nhất của hai nửa trái và phải của số N.

**Input**

Dòng đầu ghi số bộ test (không quá 10)

Mỗi bộ test ghi một số N, không quá 18 chữ số.

**Output**

Nếu số chữ số là lẻ thì ghi ra INVALID

Nếu số chữ số là chẵn thì in ra bội số chung nhỏ nhất của hai nửa trái và phải.

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 3  7  1220  1234567 | INVALID  60  INVALID |

## LẬP TRÌNH CƠ BẢN

### CP01003 - SỐ THUẦN NGUYÊN TỐ

Một số được coi là thuần nguyên tố nếu nó là số nguyên tố, tất cả các chữ số là nguyên tố và tổng chữ số của nó cũng là một số nguyên tố. Bài toán đặt ra là đếm xem trong một đoạn giữa hai số nguyên cho trước có bao nhiêu số thuần nguyên tố.

**Dữ liệu vào:** Dòng đầu tiên ghi số bộ test. Mỗi bộ test viết trên một dòng hai số nguyên dương tương ứng, cách nhau một khoảng trống. Các số đều không vượt quá 9 chữ số.

**Kết quả:** Mỗi bộ test viết ra số lượng các số thuần nguyên tố tương ứng.

**Ví dụ:**

 | **Input** | **Ouput** |
|---|---|
| 2  23 199  2345 6789 | 1  15 |

### CP01005 - TẦN SUẤT LẺ

Cho dãy số A\[\] gồm có N phần tử. Các phần tử trong dãy số đều xuất hiện với tần suất chẵn, chỉ có duy nhất 1 số có số lần xuất hiện là số lẻ. Nhiệm vụ của bạn là hãy tìm số này.

**Input:**

Dòng đầu tiên là số lượng bộ test T (T ≤ 10).

Mỗi test gồm số nguyên N (1≤ N ≤ 100 000), số lượng phần tử trong dãy số ban đầu. N là một số lẻ.

Dòng tiếp theo gồm N số nguyên A\[i\] (1 ≤ A\[i\] ≤ 1 000 000).

**Output:**

Với mỗi test in ra trên mỗi dòng một số nguyên là đáp án của bài toán.

**Ví dụ:**

 | Input: | Output |
|---|---|
| 2  7  1 2 3 2 3 1 3  5  1 1 3 3 2 | 3  2 |

## DYNAMIC PROGRAMMING

### DSA05008 - DÃY CON CÓ TỔNG BẰNG S

Cho N số nguyên dương tạo thành dãy A={A1, A2, ..., AN}. Tìm ra một dãy con của dãy A (không nhất thiết là các phần tử liên tiếp trong dãy) có tổng bằng S cho trước.

**Input:** Dòng đầu ghi số bộ test T (T&lt;10). Mỗi bộ test có hai dòng, dòng đầu tiên ghi hai số nguyên dương N và S (0 &lt; N ≤ 200) và S (0 &lt; S ≤ 40000). Dòng tiếp theo lần lượt ghi N số hạng của dãy A là các số A1, A2, ..., AN (0 &lt; Ai ≤ 200).

**Output:** Với mỗi bộ test, nếu bài toán vô nghiệm thì in ra “NO”, ngược lại in ra “YES”

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2  5 6    1 2 4 3 5  10 15  2 2 2 2 2 2 2 2 2 2 | YES  NO |

### DSAKT110 - NHÀ KHÔNG KỀ NHAU

Có N ngôi nhà trên một dãy phố, mỗi ngôi nhà chứa đựng một số lượng tài sản khác nhau. Một tên trộm muốn ăp cắp được nhiều nhất tài sản của dãy phố nhưng không muốn lấy tài sản của hai nhà kề nhau. Hãy cho biết, bằng cách đó tên trộm có thể đánh cắp được nhiều nhất bao nhiêu tài sản.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai dòng: dòng thứ nhất là một số N là số lượng ngôi nhà; dòng tiếp theo đưa vào N số là tài sản tương ứng trong mỗi ngôi nhà; các số được viết cách nhau một vài khoảng trống.
- T, N, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N ≤106; 1≤A\[i\] ≤107.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    6    5 5 10 100 10 5    4    3 2 7 10 | 110    13 |

## STACK

### DSA07028 - NHỊP CHỨNG KHOÁN

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

## GRAPH

### DSA09010 - KIỂM TRA TÍNH LIÊN THÔNG MẠNH

Cho đồ thị có hướng G=&lt;V, E&gt; được biểu diễn dưới dạng danh sách cạnh. Hãy kiểm tra xem đồ thị có liên thông mạnh hay không?

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm 2 dòng: dòng đầu tiên đưa vào hai số |V|, |E| tương ứng với số đỉnh và số cạnh; Dòng tiếp theo đưa vào các bộ đôi u, v tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;
 
**Output:**

- Đưa ra “YES”, hoặc “NO” theo từng dòng tương ứng với test là liên thông mạnh hoặc không liên thông mạnh.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 1  6 9  1 2 2 4 3 1 3 2 3 5 4 3 5 4 5 6 6 3 | YES |

### DSA10006 - CÂY KHUNG CỦA ĐỒ THỊ THEO THUẬT TOÁN DFS

Cho đồ thị vô hướng G=(V, E). Hãy xây dựng một cây khung của đồ thị G với đỉnh u ∈ V là gốc của cây bằng thuật toán DFS.

<a name="_Toc8394325"></a><a name="_Toc8132625">**Input**</a>

Dòng đầu tiên gồm một số nguyên T (1 ≤ T ≤ 20) là số lượng bộ test.

Tiếp theo là T bộ test, mỗi bộ test có dạng sau:

- Dòng đầu tiên gồm 3 số nguyên N=|V|, M=|E|, u (1 ≤ N ≤ 103, 1 ≤ M ≤ 105, 1 ≤ u ≤ N).
- M dòng tiếp theo, mỗi dòng gồm 2 số nguyên a, b (1 ≤ a, b ≤ N, a ≠ b) tương ứng cạnh nối hai chiều từ a tới b.
- Dữ liệu đảm bảo giữa hai đỉnh chỉ tồn tại nhiều nhất một cạnh nối.
 
<a name="_Toc8394326"></a><a name="_Toc8132626">**Output**</a>

Với mỗi bộ test, nếu tồn tại cây khung thì in ra N – 1 cạnh của cây khung với gốc là đỉnh u trên N – 1 dòng theo thứ tự duyệt của thuật toán DFS. Ngược lại nếu không tồn tại cây khung thì in ra -1.

<a name="_Toc8394327"></a><a name="_Toc8132627">**Ví dụ**</a>

 | **Input** | **Output** |
|---|---|
| 2  4 4 2  1 2  1 3  2 4  3 4  4 2 2  1 2  3 4 | 2 1  1 3  3 4  -1 |

### DSA10007 - CÂY KHUNG CỦA ĐỒ THỊ THEO THUẬT TOÁN BFS

Cho đồ thị vô hướng G=(V, E). Hãy xây dựng một cây khung của đồ thị G với đỉnh u ∈ V là gốc của cây bằng thuật toán BFS.

<a name="_Toc8394321"></a><a name="_Toc8132621">**Input**</a>

Dòng đầu tiên gồm một số nguyên T (1 ≤ T ≤ 20) là số lượng bộ test.

Tiếp theo là T bộ test, mỗi bộ test có dạng sau:

- Dòng đầu tiên gồm 3 số nguyên N=|V|, M=|E|, u (1 ≤ N ≤ 103, 1 ≤ M ≤ 105, 1 ≤ u ≤ N).
- M dòng tiếp theo, mỗi dòng gồm 2 số nguyên a, b (1 ≤ a, b ≤ N, a ≠ b) tương ứng cạnh nối hai chiều từ a tới b.
- Dữ liệu đảm bảo giữa hai đỉnh chỉ tồn tại nhiều nhất một cạnh nối.
 
<a name="_Toc8394322"></a><a name="_Toc8132622">**Output**</a>

Với mỗi bộ test, nếu tồn tại cây khung thì in ra N – 1 cạnh của cây khung với gốc là đỉnh u trên N – 1 dòng theo thứ tự duyệt của thuật toán BFS. Ngược lại nếu không tồn tại cây khung thì in ra -1.

<a name="_Toc8394323"></a><a name="_Toc8132623">**Ví dụ**</a>

 | **Input** | **Output** |
|---|---|
| 2  4 4 2  1 2  1 3  2 4  3 4  4 2 2  1 2  3 4 | 2 1  2 4  1 3  -1 |

### DSA10008 - DIJKSTRA

Cho đồ thị có trọng số không âm G=&lt;V, E&gt; được biểu diễn dưới dạng danh sách cạnh trọng số. Hãy viết chương trình tìm đường đi ngắn nhất từ đỉnh uÎV đến tất cả các đỉnh còn lại trên đồ thị.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm |E|+1 dòng: dòng đầu tiên đưa vào hai ba số |V|, |E| tương ứng với số đỉnh và uÎV là đỉnh bắt đầu; |E| dòng tiếp theo mỗi dòng đưa vào bộ ba uÎV, vÎV, w tương ứng với một cạnh cùng với trọng số canh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;
 
**Output:**

- Đưa ra kết quả của mỗi test theo từng dòng. Kết quả mỗi test là trọng số đường đi ngắn nhất từ đỉnh u đến các đỉnh còn lại của đồ thị theo thứ tự tăng dần các đỉnh.
 
 **Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 1  9 12 1  1 2 4  1 8 8  2 3 8  2 8 11  3 4 7  3 6 4  3 9 2  4 5 9  4 6 14  5 6 10  6 7 2  6 9 6 | 0 4 12 19 26 16 18 8 14 |

### DSA10009 - FLOYD

Cho đơn đồ thị vô hướng liên thông G = (V, E) gồm N đỉnh và M cạnh, các đỉnh được đánh số từ 1 tới N và các cạnh được đánh số từ 1 tới M.

Có Q truy vấn, mỗi truy vấn yêu cầu bạn tìm đường đi ngắn nhất giữa đỉnh X\[i\] tới Y\[i\].

**Input:**

- Dòng đầu tiên hai số nguyên N và M (1 ≤ N ≤ 100, 1 ≤ M ≤ N\*(N-1)/2).
- M dòng tiếp theo, mỗi dòng gồm 3 số nguyên u, v, c cho biết có cạnh nối giữa đỉnh u và v có độ dài bằng c (1 ≤ c ≤ 1000).
- Tiếp theo là số lượng truy vấn Q (1 ≤ Q ≤ 100 000).
- Q dòng tiếp theo, mỗi dòng gồm 2 số nguyên X\[i\], Y\[i\].
 
**Output:**

- Với mỗi truy vấn, in ra đáp án là độ dài đường đi ngắn nhất tìm được.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 5 6  1 2 6  1 3 7  2 4 8  3 4 9  3 5 1  4 5 2  3  1 5  2 5  4 3 | 8  10  3 |

### DSA10011 - DI CHUYỂN TRÊN BẢNG SỐ

Cho một bảng số kích thước N x M. Chi phí khi đi qua ô (i,j) bằng A\[i\]\[j\]. Nhiệm vụ của bạn là hãy tìm một đường đi từ ô (1, 1) tới ô (N, M) sao cho chi phí là nhỏ nhất. Tại mỗi ô, bạn được phép đi sang trái, sang phải, đi lên trên và xuống dưới.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi hai số nguyên N và M (1 ≤ N, M ≤ 500).
- N dòng tiếp theo, mỗi dòng gồm M số nguyên A\[i\]\[j\] (0 ≤ A\[i\]\[j\] ≤ 9).
 
**Output:**

- Với mỗi test, in ra một số nguyên là chi phí nhỏ nhất cho đường đi tìm được.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 3  4  5  0 3 1 2 9  7 3 4 9 9  1 7 5 5 3  2 3 4 2 5  1  6  0 1 2 3 4 5  5 5  1 1 1 9 9  9 9 1 9 9  1 1 1 9 9  1 9 9 9 9  1 1 1 1 1 | 24  15  13 |

### DSA10012 - ĐƯỜNG ĐI TRUNG BÌNH

Cho một đồ thị có hướng gồm N đỉnh và M cạnh. Nhiệm vụ của bạn là hãy tính khoảng cách trung bình ngắn nhất giữa hai node bất kì nếu như chúng liên thông với nhau. Input đảm bảo rằng trong một nhóm liên thông, nếu như u đi tới được v thì v cũng đi tới được v với mọi cặp u, v.

![](data:image/png;base64,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)

**Input:**Dòng đầu tiên là số lượng bộ test T (T ≤ 20). Mỗi test bắt đầu bởi hai số nguyên N và M (1 ≤ N ≤ 100, M ≤ N\*(N-1)/2). M dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v cho biết có cạnh nối đơn hướng từ u tới v.

**Output:** Với mỗi test, in ra đáp án tìm được với độ chính xác 2 chữ số sau dấu phảy.

**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 2  4 5  1 2  2 4  1 3  3 1  4 3  7 5  1 2  1 4  4 2  2 7  7 1 | 1.83  1.75 |

Giải thích test 1: Ta có

d(1, 2) = 1, d(1, 3) = 1, d(1, 4) = 2; d (2, 1) = 3, d(2, 3) = 2, d(2, 4) = 1;

d(3, 1) = 1, d(3, 2) = 2, d(3, 4) = 3; d(4, 1) = 2, d(4, 2) = 3, d(4, 3) = 1.

Trung bình bằng 22/12 = 1.83

### DSA10015 - KRUSKAL

Cho đồ thị vô hướng có trọng số G=&lt;V, E, W&gt;. Nhiệm vụ của bạn là hãy xây dựng một cây khung nhỏ nhất của đồ thị bằng thuật toán Kruskal.

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào hai số V, E tương ứng với số đỉnh và số cạnh của đồ thị; phần thứ 2 đưa vào E cạnh của đồ thị, mỗi cạnh là một bộ 3: đỉnh đầu, đỉnh cuối và trọng số của cạnh.
- T, S, D thỏa mãn ràng buộc: 1≤T≤100; 1≤V≤100; 1≤E, W≤10000.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    3 3    1 2 5  2 3 3  1 3 1    2 1    1 2 5 | 4    5 |

## DANH SÁCH

### ICPC0101 - THU GỌN DÃY SỐ

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

### ICPC0108 - SUM TRIPLE ZERO

Cho mảng A\[\] gồm N số nguyên khác nhau. Nhiệm vụ của bạn là đếm số lượng các bộ ba phần tử khác nhau có tổng là 0. Ví dụ A\[\] = {0, -1, 2, -3, 1}, ta nhận được kết quả là 2 vì có hai bộ 3: (0, -1, 1) và (2, -3, 1).

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo, mỗi dòng đưa vào một test. Mỗi test là gồm hai dòng: dòng đầu tiên đưa vào N là số lượng phần tử của mảng A\[\]; dòng tiếp theo đưa vào các phần tử A\[i\] của mảng A\[\].
- T, N, A\[i\] thỏa mãn ràng buộc : 1≤T≤100; 1≤ N≤103; -109≤ A\[i\] ≤109;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input:** | **Output:** |
|---|---|
| 2    5    0 -1 2 -3 1     5    1 -2 1 0 5 | 2    1 |

### ICPC0109 - MIN TRIPLE

Cho mảng A\[\] gồm N số nguyên.

Nhiệm vụ của bạn là tìm tổng nhỏ nhất của bộ ba số trong mảng. Ví dụ A\[\] = {1, 2, 3, 4, 5}, ta nhận được tổng nhỏ nhất của bộ ba số là 1 + 2 + 3 = 6. Chú ý nếu sử dụng kỹ thuật sắp xếp, submit lời giải của bạn sẽ bị fail.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo, mỗi dòng đưa vào một test. Mỗi test là gồm hai dòng: dòng đầu tiên đưa vào N là số lượng phần tử của mảng A\[\]; dòng tiếp theo đưa vào các phần tử A\[i\] của mảng A\[\].
- T, N, A\[i\] thỏa mãn ràng buộc : 1≤T≤100; 1≤N ≤106; -108≤ A\[i\] ≤108;
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
Ví dụ:

 | **Input:** | **Output:** |
|---|---|
| 2    7    1 2 3 0 -1 8 10     7    9 8 20 3 4 -1 0 | 0    2 |

### PY02003 - DÃY SỐ HAMMING

Dãy số nguyên dương tăng dần trong đó ước số nguyên tố lớn nhất của các số trong dãy đều không vượt quá 5 được gọi là dãy số Hamming. Ví dụ 10 = 2x5 thuộc dãy Hamming còn 26 = 2x13 không thuộc dãy Hamming.

Số 1 được coi là số đầu tiên của dãy Hamming.

Cho số nguyên dương N. Hãy xác định xem N có thuộc dãy Hamming hay không và nếu có thì thứ tự của N trong dãy Hamming là bao nhiêu.

**Input:**

Dòng đầu tiên ghi số bộ test (không quá 105).

Mỗi test ghi một số N (1 ≤ N ≤ 1018).

**Output:**

Nếu giá trị N thuộc dãy Hamming thì ghi ra thứ tự của N (tính từ 1).

Nếu không thì ghi ra “Not in sequence”

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 11  1  2  6  7  8  9  10  11  12  13  14 | 1  2  6  Not in sequence  7  8  9  Not in sequence  10  Not in sequence  Not in sequence |

### PYKT12026 - 2X-Y

Mảng a ban đầu có n số nguyên. Bạn có thể thực hiện thao tác sau nhiều lần:

\- Chọn số 2 số x và y bất kỳ trong mảng và thêm 2x – y vào mảng.

Với 1 số nguyên k, hãy kiểm tra xem bạn có thể tạo ra được số k hay không.

**Input:**

Dòng đầu tiên chứa số bộ test t (t ≤ 20).

Mỗi test có định dạng như sau:

\- Dòng đầu tiên chứa 2 số nguyên n và k (2 ≤ n ≤ 105, -109 ≤ k ≤ 109)

\- Dòng tiếp theo chứa n số nguyên ban đầu (-109 ≤ ai ≤ 109)

**Output:**

Với mỗi test, in ra “YES” nếu có thể và “NO” trong trường hợp còn lại.

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 6  2 1  1 2  3 0  2 3 7  2 -1  31415926 27182818  2 1000000000000000000  1 1000000000000000000  2 -1000000000000000000  -1000000000000000000 123  6 80  -5 -20 13 -14 -2 -11 | YES  YES  NO  YES  YES  NO |

## MẢNG

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

## XÂU KÝ TỰ

### J03038 - ĐÁNH DẤU CHỮ CÁI

Cho một xâu ký tự S chỉ có các chữ cái Tiếng Anh viết thường. Hãy đếm xem có bao nhiêu ký tự chữ cái khác nhau trong S.

**Input:** Có duy nhất một dòng chứa xâu ký tự S, độ dài không quá 100.

**Output:** Ghi ra số ký tự chữ cái khác nhau

**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| banana | 3 |

## CÂU LỆNH ĐIỀU KHIỂN

### PY01065 - PHÉP TOÁN CƠ BẢN

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

## BIẾN VÀ KIỂU DỮ LIỆU ĐƠN GIẢN

### PY01074 - TỔNG ƯỚC SỐ

Cho N số nguyên. Nhiệm vụ của bạn là phân tích các số nguyên đã cho dưới dạng tích của các thừa số nguyên tố, sau đó tính tổng các ước số nguyên tố này.

**Input:**

Dòng đầu tiên số nguyên N (1 ≤≤ N ≤ 106).

N dòng tiếp theo, mỗi dòng gồm một số nguyên có giá trị không vượt quá 2\*106.

**Output**

In ra một số nguyên là đáp án tìm được.

**Ví dụ**

 | Input: | Output: |
|---|---|
| 5  7  9  10  13  100 | 47 |

*Giải thích test:*

*7 = 7*

*9 = 3 x 3 à 3 + 3 = 6*

*10 = 2 x 5 à 2 + 5 = 7*

*13 = 13*

*100 = 2 x 2 x 5 x 5 à 2+2+5+5 = 14*

*Cộng lại, 7 + 6 + 7 + 13 + 14 = 47.*

## HÀNG ĐỢI

### S213 - SỐ LỘC PHÁT

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

### S223 - BIẾN ĐỔI SỐ TỰ NHIÊN

Cho số tự nhiên N (N&lt;10^9) và hai phép biến đổi (a), (b) dưới đây.

- **Thao tác (a)**: Trừ N đi 1 (N=N-1). Ví dụ N=17, thao tác (a) biến đổi N = N-1 =16.
- **Thao tác (b)**: N = max(u,v) nếu u\*v =N (u&gt;1, v&gt;1). Ví dụ N=16, thao tác (b) có thể biến đổi N = max(2, 8)=8 hoặc N=max(4, 4)=4.
 
Chỉ được phép sử dụng hai thao tác (a) hoặc (b), hãy biến đổi N thành 1 sao số các thao tác (a), (b) được thực hiện ít nhất. Ví dụ với N=17, số các phép (a), (b) nhỏ nhất biến đổi N thành 1 là 4 bước như sau:

 **Thao tác (a)**: N = N-1 = 17-1 = 16

 **Thao tác (b)**: 16 = max(4,4) = 4

 **Thao tác (b)**: 4 = max(2,2) = 2

 **Thao tác (a)**: 2 = 2-1 = 1

**Input:**

- Dòng đầu tiên ghi lại số tự nhiên T là số lượng Test;
- T dòng kế tiếp mỗi dòng ghi lại một bộ Test. Mỗi test là một số N.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 3  17  50  100 | 4  5  5 |

### S224 - DI CHUYỂN TRÊN BẢNG SỐ

Cho một bảng số kích thước N x M. Chi phí khi đi qua ô (i,j) bằng A\[i\]\[j\]. Nhiệm vụ của bạn là hãy tìm một đường đi từ ô (1, 1) tới ô (N, M) sao cho chi phí là nhỏ nhất. Tại mỗi ô, bạn được phép đi sang trái, sang phải, đi lên trên và xuống dưới.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi hai số nguyên N và M (1 ≤ N, M ≤ 500).
- N dòng tiếp theo, mỗi dòng gồm M số nguyên A\[i\]\[j\] (0 ≤ A\[i\]\[j\] ≤ 9).
 
**Output:**

- Với mỗi test, in ra một số nguyên là chi phí nhỏ nhất cho đường đi tìm được.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 3  4  5  0 3 1 2 9  7 3 4 9 9  1 7 5 5 3  2 3 4 2 5  1  6  0 1 2 3 4 5  5 5  1 1 1 9 9  9 9 1 9 9  1 1 1 9 9  1 9 9 9 9  1 1 1 1 1 | 24  15  13 |

## NGĂN XẾP

### S226 - BIỂU THỨC ĐÚNG

Cho biểu thức số học bất kỳ. Nhiệm vụ của bạn là xác định độ dài lớn nhất của các cặp đóng mở ngoặc đúng lồng nhau. Ví dụ với biểu thức P = “( ((X)) (((Y))) )” ta có độ dài các cặp đóng mở ngoặc lồng nhau đúng là 4.

Nếu biểu thức không đúng hãy đưa ra -1.

**Input**:

- Dòng đầu tiên đưa vào số lượng bộ test T (1 ≤ T ≤ 100)
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test là một biểu thức số học được đưa vào trên một dòng. Độ dài biểu thức không quá 106
 
**Output**:

- Đưa ra kết quả mỗi test theo từng dòng.
 
**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 2  (((X))(((Y))))  (b)((c)() | 4  -1 |

## ĐỒ THỊ

### S301 - ĐƯỜNG ĐI CÓ HƯỚNG

Cho đồ thị có hướng G=&lt;V, E&gt; được biểu diễn dưới dạng danh sách cạnh.

Hãy tìm đường đi từ đỉnh u đến đỉnh v trên đồ thị bằng **thuật toán BFS**.

**Input:**

- Dòng đầu tiên đưa vào T là số lượng bộ test.
- Những dòng tiếp theo đưa vào các bộ test. Mỗi bộ test gồm |E|+1 dòng: dòng đầu tiên đưa vào bốn số |V|, |E|, u, v tương ứng với số đỉnh, số cạnh, đỉnh xuất phát u, đỉnh kết thúc v;
- |E| dòng tiếp theo mỗi dòng đưa vào bộ đôi x, y tương ứng với một cạnh của đồ thị.
- T, |V|, |E| thỏa mãn ràng buộc: 1≤T≤100; 1≤|V|≤103; 1≤|E|≤|V|(|V|-1)/2;
 
**Output:**

- Đưa ra đường đi từ đỉnh s đến đỉnh t của mỗi test theo thuật toán BFS của mỗi test theo khuôn dạng của ví dụ dưới đây. Nếu không có đáp án, in ra -1.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 1  6 9 1 6  1 2  2 5  3 1  3 2  3 5  4 3  5 4  5 6  6 4 | 1 -&gt; 2 -&gt; 5 -&gt; 6 |

### S302 - ĐIỂM NÚT GIAO THÔNG TRỌNG YẾU

Một thành phố có N điểm nút giao thông. Các tuyến đường hai chiều được thiết kế giúp cho người dân có thể đi từ một nút bất kỳ đến tất cả các nút còn lại.

Những nút giao thông trọng yếu được định nghĩa là nút giao thông mà nếu các con đường đến nó đều bị chặn thì thành phố sẽ bị chia cắt, tức là khi đó sẽ có những cặp điểm nút không thể đi đến nhau được nữa.

Giả sử các điểm nút giao thông được đánh số từ 1 đến N. Hãy liệt kê các nút giao thông trọng yếu theo thứ tự tăng dần.

**Input**

- Dòng đầu là số bộ test (không quá 100)
- Mỗi bộ test bắt đầu với số nút giao thông N (không quá 1000) và số tuyến đường M.
- Tiếp theo là một dòng có M cặp số mô tả các tuyến đường hai chiều trong thành phố.
 
**Output**

Dòng đầu ghi ra số lượng điểm nút giao thông trọng yếu

Dòng thứ 2 lần lượt liệt kê các nút giao thông trọng yếu theo thứ tự tăng dần

**Ví dụ**

 | **Input** | **Output** |
|---|---|
| 1  5 5  1 2 1 3 2 3 2 5 3 4 | 2  2 3 |

### S308 - MẠNG XÃ HỘI HOÀN HẢO

Mạng xã hội hoàn hảo khi với mọi bộ ba X, Y, Z, nếu X kết bạn với Y, Y kết bạn với Z thì X và Z cũng phải là bạn bè của nhau trên mạng xã hội.

Hãy xác định một mạng xã hội có phải là hoàn hảo hay không? Nếu có hãy in ra “YES”, “NO” trong trường hợp ngược lại.

**Input:**

- Dòng đầu tiên là số lượng bộ test T (T ≤ 20).
- Mỗi test bắt đầu bởi 2 số nguyên N và M (N, M ≤ 100 000).
- M dòng tiếp theo, mỗi dòng gồm 2 số nguyên u, v (u #v) cho biết u và v là kết bạn với nhau trên mạng xã hội.
 
**Output:**

- Với mỗi test, in ra đáp án tìm được trên một dòng.
 
**Ví dụ:**

 | **Input:** | **Output** |
|---|---|
| 3  4 3  1 3  3 4  1 4  4 4  3 1  2 3  3 4  1 2  10 4  4 3  5 10  8 9  1 2 | YES  NO  YES |

## LÀM QUEN LẬP TRÌNH THI ĐẤU

### S52 - BIỂU DIỄN SỐ K

Cho một mảng A\[\] gồm N số nguyên dương và số K. Người ta gọi “biểu diễn số K trên mảng A\[\]” là một cách liệt kê các phần tử trong mảng A\[\] sao cho tổng các phần tử đó đúng bằng K. Các số được phép lặp lại và một cách sắp đặt lại thứ tự các số cũng được xem là một cách biểu diễn khác.

Hãy đếm số cách biểu diễn số K trên mảng A\[\].

Ví dụ với mảng A\[\] = {1, 5, 6}, K = 7 ta có 6 cách sau:

7 = 1 + 1 + 1+1 + 1 + 1+1 (lặp số 1 7 lần)

7 = 1 + 1 + 5 (lặp số 1)

7 = 1 + 5 + 1 (lặp và sắp đặt lại số 1)

7 = 1 + 6

7 = 6 + 1

**Input:**

- Dòng đầu tiên đưa vào số lượng bộ test T.
- Những dòng kế tiếp đưa vào các bộ test. Mỗi bộ test gồm hai phần: phần thứ nhất đưa vào N và K; dòng tiếp theo đưa vào N số của mảng A\[\]; các số được viết cách nhau một vài khoảng trống.
- T, N, K, A\[i\] thỏa mãn ràng buộc: 1≤T≤100; 1≤N≤1000; 1≤A\[i\]≤100.
 
**Output:**

- Đưa ra kết quả mỗi test theo từng dòng.
- Kết quả được tính theo modulo 109+7.
 
**Ví dụ:**

 | **Input** | **Output** |
|---|---|
| 2    3 7    1 5 6    4 14    12 3 1 9 | 6    150 |