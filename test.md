**Câu 1**


1.1 - 5 (supercomputer)


1.2 - 7 (petabyte)


1.3 - 5 (supercomputer) 


1.4 - 1 (virtual worlds) 


1.5 - 12 (RAM) 


1.6 - 13 (CPU) 


1.7 - 8 (datacenters) 


1.8 - 10 (multicore processors) 


1.9 - 3 (servers) 


1.10 - 9 (embedded computers) 


1.11 - 11 (VHDL) 


1.12 - 2 (desktop computers) 


1.13 - 15 (complier) 


1.14 - 21 (assembler) 


1.15 - 23 (cobol) 


1.16 - 19 (machine language) 


1.17 - 17 (instruction) 


1.18 - 24 (fortran) 


1.19 - 18 (assembly language) 


1.20 - 14 (operating systeam) 


1.21 - 22 (application software) 


1.22 - 16 (bit) 


1.23 - 14 (operating systeam) 


1.24 - 20 C


1.25 - 24 (fortran) 


1.26 - 6 (terabyte)

Dưới đây là các giải pháp cho các câu hỏi của bạn:

**Bài 3**

![image](https://github.com/AhnMaph/hello-world/assets/157342518/90c2cf3d-1fc3-42c2-9607-fa03f6cf9f31)


3.1 Hiệu suất của một bộ xử lý có thể được đo bằng số lệnh thực thi trong một giây (IPS - Instructions Per Second). IPS có thể được tính bằng cách chia tần số xung clock cho CPI (Clock Cycles Per Instruction). Vì vậy, ta có:

- P1: IPS = Clock Rate / CPI = Number Of Cycles / CPI = 2 GHz / 1.5 = 1.33 GIPS
- P2: IPS = Clock Rate / CPI = 1.5 GHz / 1.0 = 1.5 GIPS
- P3: IPS = Clock Rate / CPI = 3 GHz / 2.5 = 1.2 GIPS

Vậy, bộ xử lý P2 có hiệu suất cao nhất.

3.2 Nếu mỗi bộ xử lý chạy một chương trình trong 10 giây, tổng số chu kì và tổng số lượng lệnh tương ứng sẽ là:

- P1: Total Cycles = Clock Rate * Time = 2 GHz * 10s = 20 Giga Cycles
- Total Instructions = Total Cycles * IPC = 20 Giga Cycles * (1/CPI) = 20 Giga Cycles * (1/1.5) = 13.33 Giga Instructions
- P2: Total Cycles = Clock Rate * Time = 1.5 GHz * 10s = 15 Giga Cycles
- Total Instructions = Total Cycles * IPC = 15 Giga Cycles * (1/CPI) = 15 Giga Cycles * (1/1.0) = 15 Giga Instructions
- P3: Total Cycles = Clock Rate * Time = 3 GHz * 10s = 30 Giga Cycles
- Total Instructions = Total Cycles * IPC = 30 Giga Cycles * (1/CPI) = 30 Giga Cycles * (1/2.5) = 12 Giga Instructions

3.3 Nếu chúng ta cố giảm 30% thời gian thực thi sẽ dẫn tới việc tăng 20% CPI. Vậy, tần số xung clock mới của từng bộ xử lý tương ứng phải là bao nhiêu? 

![image](https://github.com/AhnMaph/hello-world/assets/157342518/724ee15b-deef-48bc-9261-0fde593ea0f5)

- P1: New Clock Rate = (Old CPI * (1 + 20%)) / (Old Execution Time * (1 - 30%)) = (1.5 * 1.2) / (10s * 0.7) = 2.57 GHz
- P2: New Clock Rate = (Old CPI * (1 + 20%)) / (Old Execution Time * (1 - 30%)) = (1.0 * 1.2) / (10s * 0.7) = 1.71 GHz
- P3: New Clock Rate = (Old CPI * (1 + 20%)) / (Old Execution Time * (1 - 30%)) = (2.5 * 1.2) / (10s * 0.7) = 4.29 GHz

Dưới đây là các công thức và đáp án cho các câu hỏi của bạn:

3.4 IPC (số lệnh được thực hiện trong một chu kì) cho mỗi bộ xử lý có thể được tính bằng cách chia số lượng lệnh cho số chu kì clock. Với P1, P2 và P3, ta có:

- IPC của P1 = Số lệnh / (Tần số xung clock * Thời gian) = 20.10^9 / (2 * 10^9 * 7) = 1.43
- IPC của P2 = 30.10^9 / (1.5 * 10^9 * 10) = 2
- IPC của P3 = 90.10^9 / (3 * 10^9 * 9) = 3.33

3.5 Để P2 có thể giảm thời gian thực thi bằng P1, tần số xung clock mới cho P2 có thể được tính bằng cách chia số lượng lệnh cho IPC và thời gian:

- Tần số xung clock mới cho P2 = Số lệnh / (IPC * Thời gian) = 30.10^9 / (2 * 7) = 2.14 GHz

3.6 Để giảm thời gian thực thi của P2 tới bằng của P3, số lượng lệnh mới cho P2 có thể được tính bằng cách nhân IPC, tần số xung clock và thời gian:

- Số lượng lệnh mới cho P2 = IPC * Tần số xung clock * Thời gian = 2 * 1.5 * 10^9 * 9 = 27.10^9

4.1 Để xác định bộ xử lý nào chạy nhanh hơn, ta cần tính thời gian thực thi của mỗi bộ xử lý. Thời gian thực thi (T) có thể được tính bằng công thức sau:

![image](https://github.com/AhnMaph/hello-world/assets/157342518/4a147969-28e4-4260-86ab-c8aad6ca0d6e)

4.1 Để xác định bộ xử lý nào chạy nhanh hơn, ta cần tính thời gian thực thi của mỗi bộ xử lý. Thời gian thực thi (T) có thể được tính bằng công thức sau:

$$T = \frac{{\text{{Số lệnh}} \times \text{{CPI}}}}{{\text{{Tần số xung clock}}}}$$

Trước tiên, ta cần tính CPI trung bình cho mỗi bộ xử lý dựa trên phân phối lớp lệnh của chương trình:

- CPI trung bình của P1: $CPI_{P1} = 0.1 \times 1 + 0.2 \times 2 + 0.5 \times 3 + 0.2 \times 4 = 2.6$
- CPI trung bình của P2: $CPI_{P2} = 0.1 \times 2 + 0.2 \times 2 + 0.5 \times 2 + 0.2 \times 3 = 2.2$

Sau đó, ta sử dụng công thức trên để tính thời gian thực thi cho mỗi bộ xử lý:

- Thời gian thực thi của P1: $T_{P1} = \frac{{10^6 \times 2.6}}{{1.5 \times 10^9}} = 1.73 \times 10^{-3}$ giây
- Thời gian thực thi của P2: $T_{P2} = \frac{{10^6 \times 2.2}}{{2 \times 10^9}} = 1.1 \times 10^{-3}$ giây

Vì vậy, P2 sẽ chạy nhanh hơn với chương trình này.

4.2 CPI trung bình của mỗi bộ xử lý đã được tính ở câu 4.1: $CPI_{P1} = 2.6$ và $CPI_{P2} = 2.2$.

4.3 Tổng số chu kì xung clock của chương trình trên mỗi bộ xử lý có thể được tính bằng công thức sau:

$$\text{{Số chu kì xung clock}} = \text{{Số lệnh}} \times \text{{CPI}}$$

- Số chu kì xung clock trên P1: $10^6 \times 2.6 = 2.6 \times 10^6$
- Số chu kì xung clock trên P2: $10^6 \times 2.2 = 2.2 \times 10^6$

4.4 Để tính thời gian thực thi của chương trình trên bộ xử lý 2 GHz, ta cần tính tổng số chu kì xung clock của chương trình, sau đó chia cho tần số xung clock. Tổng số chu kì xung clock của chương trình là tổng số lệnh nhân với số chu kì xung clock tương ứng của mỗi loại lệnh:

$$\text{{Tổng số chu kì xung clock}} = 500 \times 1 + 50 \times 5 + 100 \times 5 + 50 \times 2 = 1050$$

Vì vậy, thời gian thực thi của chương trình là:

$$T = \frac{{1050}}{{2 \times 10^9}} = 5.25 \times 10^{-7}$$ 


**Bài 5**

5.1 Hiệu suất đỉnh điểm (peak performance) được đạt khi CPI là thấp nhất. Vì vậy, ta có thể tính số lượng lệnh thực thi trong 1 giây như sau:

- P1: IPS = Clock Rate / CPI_min = 1.0 GHz / 1 = 1.0 GIPS (Giga Instructions Per Second)
- P2: IPS = Clock Rate / CPI_min = 1.5 GHz / 2 = 0.75 GIPS

5.2 Nếu số lệnh cần thực thi của một chương trình được chia đều cho các lớp lệnh, ngoại trừ lớp lệnh A có số lệnh gấp đôi các lớp lệnh khác. Ta cần tính tổng CPI trung bình cho mỗi bộ xử lý và so sánh chúng để xem bộ xử lý nào chạy nhanh hơn. Tổng CPI trung bình cho mỗi bộ xử lý có thể được tính như sau:

- P1: Average CPI = 2/7 * CPI_A + 1/7 * (CPI_B + CPI_C + CPI_D + CPI_E)
- P2: Average CPI = 2/7 * CPI_A + 1/7 * (CPI_B + CPI_C + CPI_D + CPI_E)

**Bài 5**

5.3 Nếu số lệnh cần thực thi của một chương trình được chia đều cho các lớp lệnh, ngoại trừ lớp E có số lệnh gấp đôi các lớp lệnh khác. Ta cần tính tổng CPI trung bình cho mỗi bộ xử lý và so sánh chúng để xem bộ xử lý nào chạy nhanh hơn. Tổng CPI trung bình cho mỗi bộ xử lý có thể được tính như sau:

- P1: Average CPI = 1/6 * CPI_A + 1/6 * CPI_B + 1/6 * CPI_C + 1/6 * CPI_D + 2/6 * CPI_E
- P2: Average CPI = 1/6 * CPI_A + 1/6 * CPI_B + 1/6 * CPI_C + 1/6 * CPI_D + 2/6 * CPI_E

Bộ xử lý với CPI trung bình thấp hơn sẽ chạy nhanh hơn. Để xác định bộ xử lý nào chạy nhanh hơn bao nhiêu lần, chúng ta có thể chia CPI trung bình của bộ xử lý chậm hơn cho CPI trung bình của bộ xử lý nhanh hơn.

5.4 Giả sử rằng lệnh tính toán (Compute) mất 1 chu kì, lệnh đọc dữ liệu từ bộ nhớ (Load) và ghi dữ liệu vào bộ nhớ (Store) mất 10 chu kì và lệnh rẽ nhánh (Branch) mất 3 chu kì. Thời gian thực thi của một chương trình chạy trên bộ xử lý MIPS 3 GHz có thể được tính như sau:

- Program 1: Execution Time = (Compute * 1 + Load * 10 + Store * 10 + Branch * 3) / (3 * 10^9) = (1000 * 1 + 400 * 10 + 100 * 10 + 50 * 3) / (3 * 10^9) seconds
- Program 2: Execution Time = (Compute * 1 + Load * 10 + Store * 10 + Branch * 3) / (3 * 10^9) = (1500 * 1 + 300 * 10 + 100 * 10 + 100 * 3) / (3 * 10^9) seconds

5.5 Giả sử rằng lệnh tính toán (Compute) mất 1 chu kì, lệnh đọc dữ liệu từ bộ nhớ (Load) và ghi vào bộ nhớ (Store) mất 2 chu kì và lệnh rẽ nhánh (Branch) mất 3 chu kì. Thời gian thực thi của một chương trình chạy trên bộ xử lý MIPS 3 GHz có thể được tính như sau:

- Program 1: Execution Time = (Compute * 1 + Load * 2 + Store * 2 + Branch * 3) / (3 * 10^9) = (1000 * 1 + 400 * 2 + 100 * 2 + 50 * 3) / (3 * 10^9) seconds
- Program 2: Execution Time = (Compute * 1 + Load * 2 + Store * 2 + Branch * 3) / (3 * 10^9) = (1500 * 1 + 300 * 2 + 100 * 2 + 100 * 3) / (3 * 10^9) seconds
