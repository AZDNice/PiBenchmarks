# PiBenchmarks
Raspberry Pi benchmarking scripts featuring a storage benchmark with a score<br>
Anonymously uploads your score to jamesachambers.com to help others make good decisions on Pi storage<br>
View current benchmarks at: https://www.jamesachambers.com/raspberry-pi-storage-benchmarks/<br>
Discussion and analysis at: https://jamesachambers.com/2019/03/raspberry-pi-storage-benchmarks-2019-benchmarking-script/<br>
<br>
To run the benchmark type/paste:<br>
curl https://raw.githubusercontent.com/TheRemote/PiBenchmarks/master/Storage.sh | sudo bash<br>
<br>
<b>Update History</b><br>
<br>
April 27th 2019<br>
-Added cross platform CPU frequency detection to use if vcgencmd is not present<br>
-Improved boot drive detection<br>
-Added fallback for SD drivers that don't populate the udevadm information<br>
<br>
April 16th 2019<br>
-Added "Team Group" MicroSD vendor (code -B, 0x000045)<br>
-Added Maxell MicroSD vendor (code TI)<br>
-Added fix to get gpu_freq on older Raspberry Pis that don't have core_freq<br>
<br>
March 30th 2019<br>
-Added x86_64 and x86 support<br>
<br>
March 29th 2019<br>
-Added Transcend to known vendors<br>
-Eliminated wget dependency (uses pure curl for everything)<br>
-Attempt to use native iozone package if available, otherwise build<br>
<br>
March 18th 2019<br>
-Added Arch Linux support<br>
<br>
March 17th 2019<br>
-Added Ubuntu support<br>
<br>
March 16th 2019<br>
-Initial release<br>