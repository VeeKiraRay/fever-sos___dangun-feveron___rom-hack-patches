# Change default top-5 disco men count
No real benefit to this change but was interesting to find this info in the binary by searhing the default values as a pattern. The defaults are 1000, 900, 800, 700 and 600. This patch will change them to 5, 4, 3, 2 and 1.

The two first digits are stored in the rom 34 and the two last digits are on the rom 33. They are both stored in the same address of 0x31b31.

![Alt text](preview.jpg?raw=true "Preview picture")