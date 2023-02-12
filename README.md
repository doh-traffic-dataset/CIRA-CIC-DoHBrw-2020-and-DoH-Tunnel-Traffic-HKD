
# The CIRA-CIC-DoHBrw-2020 and DoH-Tunnel-Traffic-HKD combined dataset

* The dataset (CIRA-CIC-DoHBrw-2020-and-DoH-Tunnel-Traffic-HKD.zip) is available on the Hokkaido University website - https://eprints.lib.hokudai.ac.jp/dspace/handle/xxxx/xxxx.

* The "l1-total-add.csv" contains traffic flows of Non-DoH 897493 and DoH 374803.

* The "l2-total-add.csv" includes traffic flows of Normal DoH 19807 and Suspicious DoH 354996.

* The "l3-total-add.csv" encloses traffic flows of dns2tcp 167486, dnscat2 35770, iodine 46580, dnstt 46080, tcp-over-dns 30040, and tuns 29040.

* Note that the "l1-total-add.csv" is currently too large to open in Microsoft Excel.
  Use a text editor such as Vim to view its contents.

# License

* The dataset has data from the CIRA-CIC-DoHBrw-2020 [1] and DoH-Tunnel-Traffic-HKD [2] datasets.

* If you use the dataset, please be sure to cite both following papers in your paper.

* Mohammadreza MontazeriShatoori, Logan Davidson, Gurdip Kaur, and Arash Habibi Lashkari, 
"Detection of DoH Tunnels using Time-series Classification of Encrypted Traffic," 
*The 5th IEEE Cyber Science and Technology Congress*, Calgary, Canada, August 2020. https://ieeexplore.ieee.org/document/9251211

* Rikima Mitsuhashi, Yong Jin, Katsuyoshi Iida, Takahiro Shinagawa, and Yoshiaki Takai, 
"Malicious DNS Tunnel Tool Recognition using Persistent DoH Traffic Analysis,"
*in IEEE Transactions on Network and Service Management*, 2022. https://ieeexplore.ieee.org/document/9924534

# References

* [1] CIRA-CIC-DoHBrw-2020 (https://www.unb.ca/cic/datasets/dohbrw-2020.html)
* [2] DoH-Tunnel-Traffic-HKD (https://github.com/doh-traffic-dataset/DoH-Tunnel-Traffic-HKD/)
