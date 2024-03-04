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


**Bài 2.1**
- Mỗi pixel sử dụng 8 bit cho mỗi màu cơ bản (red, green, blue), tổng cộng là 24 bit hoặc 3 byte/pixel.
- Độ phân giải của màn hình là 1280x800 = 1,024,000 pixel.
- Vậy, độ lớn của bộ đệm để chứa một khung ảnh là: 1,024,000 pixel * 3 byte/pixel = 3,072,000 byte hoặc 3 MB.

**Bài 2.2**
- Bộ nhớ chính của máy tính là 2048 MB.
- Vậy, số khung ảnh tối đa mà bộ nhớ có thể chứa là: 2048 MB / 3 MB/khung ảnh = 682.67 khung ảnh.
- Tuy nhiên, vì không thể chứa một phần của khung ảnh, nên số khung ảnh tối đa mà bộ nhớ có thể chứa là 682 khung ảnh.

**Bài 2.3**
- Tốc độ của mạng Ethernet là 1 Gb/s = 125 MB/s.
- Dung lượng của tệp là 256 KB = 0.256 MB.
- Vậy, thời gian cần để gửi tệp là: 0.256 MB / 125 MB/s = 0.002048 giây.

**Bài 2.4**
- Thời gian để đọc một file từ bộ nhớ cache là 2µs.
- Vậy, thời gian để đọc file từ DRAM là: 2µs * (50ns / 5ns) = 20µs.
- Thời gian để đọc file từ Flash Memory là: 2µs * (5µs / 5ns) = 2000µs = 2ms.
- Thời gian để đọc file từ Magnetic Disk là: 2µs * (5ms / 5ns) = 2,000,000µs = 2 giây.

**Bài 3.1**
- Hiệu suất của một bộ xử lý được đo bằng số lệnh thực thi trong một giây (IPS) hoặc số 10^6 lệnh thực thi trong một giây (MIPS).
- IPS = Clock Rate / CPI.
- MIPS = IPS / 1,000,000.
- IPS và MIPS của P1: IPS = 2 GHz / 1.5 = 1.33 GIPS, MIPS = 1333 MIPS.
- IPS và MIPS của P2: IPS = 1.5 GHz / 1.0 = 1.5 GIPS, MIPS = 1500 MIPS.
- IPS và MIPS của P3: IPS = 3 GHz / 2.5 = 1.2 GIPS, MIPS = 1200 MIPS.
- Vậy, P2 có hiệu suất cao nhất.

**Bài 3.2**
- Số cycle = Executation Time * Clock Rate.
- Number of Instructions = Số cycle * CPI.
- Số cycle và Number of Instructions của P1: Số cycle = 10s * 2 GHz = 20 tỷ cycle, Number of Instructions = 20 tỷ cycle / 1.5 = 13.33 tỷ lệnh.
- Số cycle và Number of Instructions của P2: Số cycle = 10s * 1.5 GHz = 15 tỷ cycle, Number of Instructions = 15 tỷ cycle / 1.0 = 15 tỷ lệnh.
- Số cycle và Number of Instructions của P3: Số cycle = 10s * 3 GHz = 30 tỷ cycle, Number of Instructions = 30 tỷ cycle / 2.5 = 12 tỷ lệnh.

**Bài 3.3**

![image](https://github.com/AhnMaph/hello-world/assets/157342518/3f2dcd00-ef29-4bb8-a4ec-d1992f7d68c9)


- Nếu giảm 30% Executation Time thì Clock Rate mới = Clock Rate cũ / (1 - 0.3) = 1.43 * Clock Rate cũ.
- Nếu tăng 20% CPI thì Clock Rate mới = Clock Rate cũ * (1 + 0.2) = 1.2 * Clock Rate cũ.
- Vậy, Clock Rate mới của P1 = 1.43 * 2 GHz = 2.86 GHz.
- Clock Rate mới của P2 = 1.43 * 1.5 GHz = 2.145 GHz.
- Clock Rate mới của P3 = 1.43 * 3 GHz = 4.29 GHz.

**Bài 3.4**
- IPC = Số lệnh / Số cycle= Clock Rate * Time * CPI / Số Cycle = Clock Rate / Executation Time.
- IPC của P1 = 2 GHz / 7s = 0.286 GIPS.
- IPC của P2 = 1.5 GHz / 10s = 0.15 GIPS.
- IPC của P3 = 3 GHz / 9s = 0.333 GIPS.

**Bài 3.5**
- Để P2 có thể giảm Executation Time bằng P1 thì Clock Rate mới của P2 = Clock Rate của P1 * (Executation Time của P1 / Executation Time của P2) = 2 GHz * (7s / 10s) = 1.4 GHz.

**Bài 3.6**
- Để P2 giảm Executation Time tới bằng của P3 thì Number of Instructions mới của P2 = Số lệnh của P3 * (Executation Time của P3 / Executation Time của P2) = 90.10^9 * (9s / 10s) = 81.10^9 lệnh.

**Bài 4.1**
- Executation Time của một chương trình = Tổng số lệnh * CPI / Clock Rate.
- CPI trung bình của P1 = (10% * 1 + 20% * 2 + 50% * 3 + 20% * 4) = 2.6.
- CPI trung bình của P2 = (10% * 2 + 20% * 2 + 50% * 2 + 20% * 3) = 2.2.
- Executation Time của P1 = 10^6 * 2.6 / 1.5 GHz = 1.73 ms.
- Executation Time của P2 = 10^6 * 2.2 / 2 GHz = 1.1 ms.
- Vậy, P2 sẽ chạy nhanh hơn với chương trình này.

**Bài 4.2**
- CPI trung bình của P1 = 2.6.
- CPI trung bình của P2 = 2.2.

**Bài 4.3**
- Number of clock cycles của chương trình trên P1 = Tổng số lệnh * CPI trung bình = 10^6 * 2.6 = 2.6 10^6 cycle.
- Number of clock cycles của chương trình trên P2 = Tổng số lệnh * CPI trung bình = 10^6 * 2.2 = 2.2 10^6 cycle.

**Bài 4.4**
- Executation Time của chương trình = Tổng số lệnh * CPI / Clock Rate.
- CPI trung bình = (500 * 1 + 50 * 5 + 100 * 5 + 50 * 2) / 700 = 2.5.
- Executation Time của chương trình = 700 * 2.5 / 2 GHz = 0.875 ms.
Dưới đây là các giải pháp cho các câu hỏi của bạn:

**4.4** Executation Time của chương trình được tính bằng cách nhân tổng số cycle với thời gian mỗi cycle (1 / tần số xung nhịp). Tổng số cycle là tổng số lệnh nhân với số cycle mỗi lệnh.

Tổng số cycle = 500 * 1 (Arith) + 50 * 5 (Store) + 100 * 5 (Load) + 50 * 2 (Branch) = 500 + 250 + 500 + 100 = 1350 cycle

Executation Time = Tổng số cycle / Tần số xung nhịp = 1350 / 2 GHz = 675 ns

**4.5** CPI (cycle trên mỗi lệnh) được tính bằng cách chia tổng số cycle cho tổng số lệnh.

CPI = Tổng số cycle / Tổng số lệnh = 1350 / 700 = 1.93

**4.6** Nếu Number of Instructions load giảm một nửa, thì tổng số cycle sẽ giảm và CPI cũng sẽ giảm. Speedup được tính bằng cách chia Executation Time ban đầu cho Executation Time mới.

Number of cycles = 500 * 1 (Arith) + 50 * 5 (Store) + 50 * 5 (Load mới) + 50 * 2 (Branch) = 500 + 250 + 250 + 100 = 1100 cycle

Executation Time mới = Number of cycles / Tần số xung nhịp = 1100 / 2 GHz = 550 ns

CPI mới = Number of cycles / Tổng số lệnh = 1100 / 650 = 1.69

Speedup = Executation Time ban đầu / Executation Time mới = 675 ns / 550 ns = 1.23 lần

**5.1**

![image](https://github.com/AhnMaph/hello-world/assets/157342518/d56be8c4-93df-42bc-8c57-ec8e967bb70e)


Hiệu suất đỉnh điểm (peak performance) của một bộ xử lý được đạt khi nó thực thi lớp lệnh có CPI thấp nhất. Vì vậy, Number of Instructions thực thi trong 1 giây khi P1 và P2 đạt hiệu suất đỉnh điểm có thể được tính như sau:

- P1: $$\frac{1.0 \times 10^9}{1} = 1.0 \times 10^9$$ lệnh/giây
- P2: $$\frac{1.5 \times 10^9}{2} = 0.75 \times 10^9$$ lệnh/giây

**5.2** Nếu số lệnh cần thực thi của một chương trình được chia đều cho các lớp lệnh, ngoại trừ lớp lệnh A có số lệnh gấp đôi các lớp lệnh khác. Máy tính nào chạy nhanh hơn và nhanh hơn bao nhiêu lần?

Giả sử rằng có tổng cộng N lệnh, với 2N/7 lệnh thuộc lớp A và N/7 lệnh thuộc mỗi lớp lệnh còn lại. Clock Cycles cần thiết cho P1 và P2 có thể được tính như sau:

- P1: $$2N/7 \times 1 + 5N/7 \times 2 = 2N/7 + 10N/7 = 12N/7$$ cycle
- P2: $$2N/7 \times 2 + 5N/7 \times 2 = 4N/7 + 10N/7 = 14N/7$$ cycle

Vì vậy, P1 sẽ chạy nhanh hơn P2 và nhanh hơn $$\frac{14N/7}{12N/7} = 1.17$$ lần.

**5.3** Nếu Number of Instructions cần thực thi của một chương trình được chia đều cho các lớp lệnh, ngoại trừ lớp E có số lệnh gấp đôi các lớp lệnh khác. Máy tính nào chạy nhanh hơn và nhanh hơn bao nhiêu lần?

Giả sử rằng có tổng cộng N lệnh, với 2N/7 lệnh thuộc lớp E và N/7 lệnh thuộc mỗi lớp lệnh còn lại. Clock Cycles cần thiết cho P1 và P2 có thể được tính như sau:

- P1: $$2N/7 \times 3 + 5N/7 \times 2 = 6N/7 + 10N/7 = 16N/7$$ cycle
- P2: $$2N/7 \times 4 + 5N/7 \times 2 = 8N/7 + 10N/7 = 18N/7$$ cycle

Vì vậy, P1 sẽ chạy nhanh hơn P2 và nhanh hơn $$\frac{18N/7}{16N/7} = 1.125$$ lần.

**5.4** Giả sử rằng lệnh tính toán (Compute) mất 1 cycle, lệnh đọc dữ liệu từ bộ nhớ (Load) và ghi dữ liệu vào bộ nhớ (Store) mất 10 cycle và lệnh rẽ nhánh (Branch) mất 3 cycle. Dựa vào bảng dữ liệu trên hãy tính Executation Time của một bộ xử lý MIPS 3 GHz.

Executation Time của một chương trình trên một bộ xử lý có thể được tính bằng cách chia tổng Clock Cycles cần thiết cho tần số xung nhịp. Clock Cycles cần thiết cho Program 1 và Program 2 có thể được tính như sau:

- Program 1: $$1000 \times 1 + 400 \times 10 + 100 \times 10 + 50 \times 3 = 1000 + 4000 + 1000 + 150 = 6150$$ cycle
- Program 2: $$1500 \times 1 + 300 \times 10 + 100 \times 10 + 100 \times 3 = 1500 + 3000 + 1000 + 300 = 5800$$ cycle

Vì vậy, Executation Time của Program 1 và Program 2 trên một bộ xử lý MIPS 3 GHz sẽ là:

- Program 1: $$\frac{6150}{3 \times 10^9} = 2.05 \times 10^{-6}$$ giây
- Program 2: $$\frac{5800}{3 \times 10^9} = 1.93 \times 10^{-6}$$ giây

**5.5** Giả sử rằng lệnh tính toán (Compute) mất 1 cycle, lệnh đọc dữ liệu từ bộ nhớ (Load) và ghi vào bộ nhớ (Store) mất 2 cycle và lệnh rẽ nhánh (Branch) mất 3 cycle. Dựa vào bảng dữ liệu trên hãy tính Executation Time của một bộ xử lý MIPS 3GHz.

Clock Cycles cần thiết cho Program 1 và Program 2 có thể được tính như sau:

- Program 1: $$1000 \times 1 + 400 \times 2 + 100 \times 2 + 50 \times 3 = 1000 + 800 + 200 + 150 = 2150$$ cycle
- Program 2: $$1500 \times 1 + 300 \times 2 + 100 \times 2 + 100 \times 3 = 1500 + 600 + 200 + 300 = 2600$$ cycle

Vì vậy, Executation Time của Program 1 và Program 2 trên một bộ xử lý MIPS 3 GHz sẽ là:

- Program 1: $$\frac{2150}{3 \times 10^9} = 7.17 \times 10^{-7}$$ giây
- Program 2: $$\frac{2600}{3 \times 10^9} = 8.67 \times 10^{-7}$$ giây
