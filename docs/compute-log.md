==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 11
Version:    10.0.26200
Machine:    AMD64
Processor:  Intel64 Family 6 Model 186 Stepping 2, GenuineIntel
Python:     3.13.3 (tags/v3.13.3:6280bb5, Apr  8 2025, 14:47:33) [MSC v.1943 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.0454 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0434 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0070 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.0454s
  list benchmark:   0.0434s
  string benchmark: 0.0070s
  ## RAM
=======================================================
Total RAM: 8.0 GB