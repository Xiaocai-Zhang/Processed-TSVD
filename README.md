# Towards Safer Cities: A Safety-Oriented Framework for Urban Traffic Signal Control Testing and Enhancement
The processed dataset spans from 2014 to 2025. It is organized by year, with each year stored as a separate .npy file. Each file has a shape of (N, 12), where N is the number of time steps. The meaning of each of the 12 dimensions (D1 to D12) is illustrated in the following table. For example, D1 represents the traffic flow from North (N) to East (E).
|      | N | E | S | W |
|------|------|------|------|------|
| N |  0   |  D1   |  D2   |  D3   |
| E |  D4   |  0   |  D5   |  D6   |
| S |  D7   | D8   | 0   | D9   |
| W | D10   | D11   | D12   | 0   |
