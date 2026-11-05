Disk Scheduling:

Definition
Disk scheduling determines the order in which disk I/O requests are serviced.

Algorithms
1. FCFS – Services requests in arrival order.
2. SSTF – Services the request closest to the current head position.
3. SCAN – Moves across the disk in one direction and then reverses.
4. C-SCAN – Services requests in one direction and returns to the beginning.
5. LOOK – Similar to SCAN but reverses at the last pending request.
6. C-LOOK – Similar to C-SCAN but jumps between the last and first pending requests.

Performance Factors
- Seek Time
- Rotational Latency
- Transfer Time
- Disk Throughput

Conclusion
Disk scheduling improves storage performance and reduces unnecessary disk-head movement.
