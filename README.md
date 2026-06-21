# Operating-Systems-05-2569
<p>
เนื้อหาวิชา Operating Systems สอนที่
<a href="https://cs.sci.tu.ac.th/">สาขาวิชาวิทยาการคอมพิวเตอร์</a> 
<a href=""https://sci.tu.ac.th/>คณะวิทยาศาสตร์และเทคโนโลยี</a> 
<a href=""https://tu.ac.th/>มหาวิทยาลัยธรรมศาสตร์</a> 
ภาค 2 ปีการศึกษา 2568 สอนจบเมื่อเดือน พฤษภาคม 2569 
</p>
<p>
  <b>Textbooks:</b> 
  <ol>
    <li><b>OSC10:</b> <a href="https://archive.org/details/silberschatz-operating-system-concepts-10e-2018">Operating System Concepts, 10th Edition</a>โดย  
<a href="https://codex.cs.yale.edu/avi/">Avi Silberschatzi</a>, 
<a href="https://dl.acm.org/profile/81100611528">Peter B. Galvin</a>, 
<a href="https://greggagne.github.io/">Greg Gagne</a> 
สามารถดาวน์โหลดได้ฟรีจาก The Internet Archive.
</li>
    <li><b>OSTEP:</b><a href="https://pages.cs.wisc.edu/~remzi/OSTEP/">Operating Systems: Three easy pieces (OSTEP)</a> เป็นหนังสือ Free Text book ที่เขียนโดย 
<a href="https://pages.cs.wisc.edu/~remzi/">Prof. Ramzi H. Arpaci-Dusseau</a> 
และ 
<a href="https://pages.cs.wisc.edu/~dusseau/">Prof. Andrea C. Arpaci-Dusseau 
จาก University of Wisconsin Madison</li>
    <li><b>APUE:</b><a href="https://www.amazon.com/dp/0321637739?lv=shuf&channelId=500&plpRedirect=mhFallback">Advanced Programming in the UNIX Environment, 3rd Edition</a> โดย  
<a href="https://en.wikipedia.org/wiki/W._Richard_Stevens">W. Stevens</a>, 
<a href="https://www.informit.com/authors/bio/9d0900f8-cd4c-4976-8949-62c1e58512f6">Stephen Rago</a>
หาซื้อ Kindle Edition ได้ที่ Amazon 
  </ol>
</p>
<p>
  <b>เนื้อหา:</b> 
  <table>
  <thead>
    <tr>
      <th>ครั้งที่</th>
      <th>หัวข้อและเนื้อหา (สรุป YT วิดีโอโดย gemini ai)</th>
      <th>อ้างอิง</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Lecture 1: แนะนำ บบปฏิบัติการ    ความสำคัญของระบบปฏิบัติการ 
        <ul>
          <li>Video: <a href="https://youtu.be/gWHLBOhPRS0">Lecture 1</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-01.pdf">Slide 1</a></li>
          <li>
<details>
<summary>สรุป</summary>
        <ol>
<li>
ความสำคัญของระบบปฏิบัติการ (OS) [04:00]: ยกตัวอย่างระบบปฏิบัติการรอบตัว เช่น Windows, iOS, Android รวมถึงความสำคัญของ Linux ที่แฝงอยู่ในชีวิตประจำวันและการทำงาน
<li>
กรณีศึกษาหน้าที่ของ OS [01:03:49]: ยกตัวอย่างเบื้องหลังความสำเร็จของ Microsoft ในการจัดการหน่วยความจำ (Memory Management) เพื่อเพิ่มประสิทธิภาพการทำงานของระบบและโปรแกรม ซึ่งถือเป็นหน้าที่หลักประการหนึ่งของระบบปฏิบัติการ
        </ol>
</details>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>2</td>
      <td>Lecture 2: บทบาทและหน้าที่ของ OS ส่วนประกอบของระบบคอมพิวเตอร์
        <ul>
          <li>Video: <a href="https://youtu.be/nSAnVHrKCsg">Lecture 2</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-02.pdf">Slide 2</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>บทบาทและหน้าที่ของ OS [03:17]: อธิบายถึงหน้าที่หลักของระบบปฏิบัติการ (OS) ในการอำนวยความสะดวกให้ผู้ใช้ ช่วยบริหารจัดการทรัพยากร และควบคุมให้การรันโปรแกรมหรือแอปพลิเคชันต่าง ๆ เป็นไปอย่างมีประสิทธิภาพ [04:23]
<li>ส่วนประกอบของระบบคอมพิวเตอร์ [05:18]: อธิบายโครงสร้างและเลเยอร์ต่าง ๆ ของคอมพิวเตอร์ ตั้งแต่ฮาร์ดแวร์, ระบบปฏิบัติการ, ไปจนถึงระดับแอปพลิเคชัน (เช่น Web Browser หรือเกม) [07:36] ที่ผู้ใช้โต้ตอบด้วย
<li>การทำงานร่วมกันระหว่าง CPU และ Memory [01:25:10]: อธิบายกลไกของ Machine Cycle และการรับ-ส่งข้อมูลในคอมพิวเตอร์ปัจจุบัน ที่ CPU ต้องทำหน้าที่คัดลอก (Copy) ข้อมูลผ่านบัส (Bus) มาเก็บไว้ที่หน่วยความจำสำรองความเร็วสูง (Register) ก่อนทำการประมวลผล แล้วจึงส่งกลับไปยังหน่วยความจำหลัก (Memory) [01:26:07]
</ol>
</details></li>
          <li>Video: <a href="https://youtu.be/9BSzJY6dZO8">Additional: Number and Information</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>ภาพรวมและแนวคิดเรื่อง Virtualization [00:06]: ทบทวนแนวคิดเรื่อง Virtualization และอธิบายว่าระบบปฏิบัติการ (OS) เช่น Linux หรือ Android แท้จริงแล้วก็คือซอฟต์แวร์ที่สร้างสภาพแวดล้อมจำลอง (Virtualization) ขึ้นมาทำงานบนฮาร์ดแวร์จริง
<li>
ความเข้าใจเบื้องต้นเกี่ยวกับข้อมูลในระบบคอมพิวเตอร์ [03:47]: อธิบายถึงความเป็นรูปธรรมและนามธรรมของข้อมูล ซึ่งในระบบคอมพิวเตอร์ข้อมูลและคำสั่งต่างๆ จะถูกจัดเก็บและประมวลผลผ่านสัญญาณไฟฟ้า
<li>
การแปลงเลขฐานและโครงสร้างบิต [57:44]: อธิบายวิธีและหลักการแปลงเลขฐานที่ใช้ในระบบคอมพิวเตอร์ โดยเฉพาะความสัมพันธ์และการแปลงค่าไปมาระหว่าง เลขฐานสอง (Binary), เลขฐานแปด (Octal) และเลขฐานสิบหก (Hexadecimal) [59:01] เช่น การจัดกลุ่มบิต (Group ทีละ 3 บิตสำหรับฐานแปด) เพื่อนำไปใช้ทำความเข้าใจพฤติกรรมและการทำงานของ OS ในระดับลึกต่อไป
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>3</td>
      <td>Lecture 3: สถาปัตยกรรมคอมพิวเตอร์และระบบบัส กลไกการควบคุมของระบบปฏิบัติการ 
        <ul>
          <li>Video: <a href="https://youtu.be/4rOKCWfD5eA">Lecture 3</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-02.pdf">Slide 2 </a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
สถาปัตยกรรมคอมพิวเตอร์และระบบบัส [06:48]: ทบทวนความรู้เรื่องระบบบัส (Bus) ซึ่งเป็นวงจรอิเล็กทรอนิกส์ที่ทำหน้าที่ส่งสัญญาณและถ่ายโอนข้อมูลระหว่างอุปกรณ์ต่างๆ ภายในคอมพิวเตอร์
<li>
กลไกการควบคุมของระบบปฏิบัติการ [01:11:43]: อธิบายถึงบทบาทของนักพัฒนา OS ในการเขียนโค้ดและวางแผนล่วงหน้าเพื่อรองรับเหตุการณ์ (Events) ต่างๆ ที่เกิดขึ้นในระบบ เพื่อให้การทำงานร่วมกันระหว่างฮาร์ดแวร์และซอฟต์แวร์เป็นไปอย่างราบรื่นจนกระทั่งปิดเครื่อง
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>4</td>
      <td>Lecture 4: กลไกการทำงานของ Interrupt  การทำงานของอวัยวะคอมพิวเตอร์   (เปรียบเทียบ)
        <ul>
          <li>Video: <a href="https://youtu.be/6p3zMUV2ULg">Lecture 4</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-02.pdf">Slide 2</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
กลไกการทำงานของ Interrupt [00:06]: อธิบายเรื่องกลไกการขัดจังหวะ (Interrupt) ซึ่งเป็นวิวัฒนาการสำคัญของ CPU ที่ช่วยให้ระบบคอมพิวเตอร์ตอบสนองและจัดการเหตุการณ์ต่างๆ ที่เกิดขึ้นจากอุปกรณ์รับ-ส่งข้อมูล (I/O Devices) ได้ทันที [02:32]
<li>
การทำงานของอวัยวะคอมพิวเตอร์ [03:12]: เปรียบเทียบ CPU เป็นสมอง หน่วยความจำเป็นส่วนเก็บความจำ [04:37] และอุปกรณ์ I/O ต่างๆ เช่น เมาส์ คีย์บอร์ด จอภาพ เป็นอวัยวะ [05:58] ที่ต้องประสานงานกับ CPU เพื่อโต้ตอบกับผู้ใช้และโลกภายนอก
<li>
สถาปัตยกรรมตัวจัดการ Interrupt [01:21:11]: อธิบายหน้าที่และการทำงานร่วมกันของฮาร์ดแวร์อย่าง Local APIC และ I/O APIC ในคอมพิวเตอร์ปัจจุบัน ที่ช่วยจัดลำดับความสำคัญ (Priority) และส่งสัญญาณ Interrupt ไปยัง CPU Core ที่เหมาะสมได้อย่างถูกต้อง [01:21:38]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>5</td>
      <td>Lecture 5: ทบทวนกลไกการขัดจังหวะ (Interrupt) หน่วยความจำ
        <ul>
          <li>Video: <a href="https://youtu.be/7mwmE_W1O8I">Lecture 5</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-03.pdf">Slide 3</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
กลไกและการเกิด Interrupt [02:29]: ทบทวนกลไกการขัดจังหวะ (Interrupt) โดยเปรียบเทียบกับชีวิตประจำวันที่มีสิ่งเร้าเข้ามาพร้อมกันหลายรูปแบบ [04:30] ซึ่งในคอมพิวเตอร์สามารถเกิดการขัดจังหวะได้จากทั้งซอฟต์แวร์ประมวลผลภายในตัว CPU เอง และจากอุปกรณ์ I/O ภายนอก [05:31] โดยมีฮาร์ดแวร์คอยช่วยคัดกรองส่งสัญญาณไปยัง CPU Core ที่ถูกต้อง [08:05]
<li>
ความสำคัญของระบบ Cache Memory [01:25:32]: อธิบายถึงหลักการเก็บและดึงข้อมูลที่ใช้บ่อยของหน่วยความจำแคช (Cache) ซึ่งเป็นสถาปัตยกรรมสำคัญที่ช่วยให้ CPU ทำงานได้เร็วขึ้นอย่างก้าวกระโดด และสอดคล้องกับพฤติกรรมการเรียกใช้ข้อมูลของระบบคอมพิวเตอร์ในปัจจุบัน [01:26:31]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>6</td>
      <td>Lecture 6: โครงสร้างและลำดับชั้นของหน่วยความจำ    แนวคิดการทำงานแบบ Multiprogramming 
        <ul>
          <li>Video: <a href="https://youtu.be/W8glao6cvmo">Lecture 6</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-03.pdf">Slide 3</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
โครงสร้างและลำดับชั้นของหน่วยความจำ (Storage Hierarchy) [04:10]: อธิบายธรรมชาติและการจัดลำดับของหน่วยความจำในระบบคอมพิวเตอร์ ตั้งแต่หน่วยความจำความเร็วสูงขนาดเล็กที่อยู่ใกล้ชิด CPU อย่าง Register [05:30] ไปจนถึงหน่วยความจำหลัก (Main Memory) ที่อยู่ห่างออกไป [06:23]
<li>
แนวคิดการทำงานแบบ Multiprogramming [01:18:53]: อธิบายกลไกที่ทำให้คอมพิวเตอร์ปัจจุบันสามารถรันโปรแกรมหลายๆ โปรแกรม (เช่น เล่นเกม พิมพ์งาน ดู Netflix) ได้พร้อมกัน โดย CPU จะสลับการทำงานไปมาระหว่างโปรแกรมอย่างรวดเร็วในระดับมิลลิวินาทีหรือไมโครวินาที ทำให้ผู้ใช้รู้สึกเหมือนระบบทำงานทุกอย่างขนานกันไป [01:19:42]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>7</td>
      <td>Lecture 7: โครงสร้างของระบบปฏิบัติการ บทบาทและบริการของ OS  กลไก Linker และ Loader
        <ul>
          <li>Video: <a href="https://youtu.be/pOB8EDmS6Kk">Lecture 7</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-04.pdf">Slide 4</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
โครงสร้างของระบบปฏิบัติการ (OS Structure) [04:24]: เริ่มต้นบทเรียนใหม่ที่ครอบคลุมเรื่องบริการต่างๆ ของ OS, หน้าต่างการใช้งาน (Interface) และการเรียกใช้งานระบบ (System Call)
<li>
บทบาทและบริการของ OS [06:06]: อธิบายว่า OS ทำหน้าที่สร้างสภาพแวดล้อมที่เหมาะสมสำหรับการทำงานและประมวลผลโปรแกรม โดยเปรียบเทียบความแตกต่างของการใช้งานเหมือนสภาพแวดล้อมในมหาวิทยาลัย [08:50]
<li>
กลไก Linker และ Loader [01:47:56]: อธิบายขั้นตอนสำคัญในการเปลี่ยนซอฟต์แวร์หรือไฟล์ที่รันได้ (Executable File) ที่หยุดนิ่งอยู่ในหน่วยความจำสำรอง (Storage) ให้กลายเป็นโปรแกรมที่กำลังทำงานอยู่ (Process) บนหน่วยความจำหลัก รวมถึงการทำงานร่วมกับ Shared Library และการเตรียมเนื้อหาเพื่อเรียนต่อในสัปดาห์หน้าก่อนสอบมิดเทอม
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>7.5</td>
      <td>Lecture 7.5: กลไกการทำงานของ Linker และแนวคิด Executable File  กระบวนการบูตระบบ (Booting Process) 
        <ul>
          <li>Video: <a href="https://youtu.be/dN9aq9PG9Cs">Lecture 7.5</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-04.pdf">Slide 4</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
กลไกการทำงานของ Linker และแนวคิด Executable File [02:49]: อธิบายขั้นตอนการแปลงซอร์สโค้ดผ่าน คอมไพเลอร์ (Compiler) ออกมาเป็น Object File หลายๆ ไฟล์ [05:56] จากนั้นตัวสร้างส่วนเชื่อมโยง (Linker) จะทำหน้าที่รวบรวมไฟล์เหล่านั้นและ Library ต่างๆ เข้าด้วยกันเพื่อสร้างเป็นไฟล์ที่พร้อมประมวลผล (Executable File) [06:47] เช่น ไฟล์ตระกูล .exe ใน Windows หรือไฟล์แบบ Binary ใน Linux [08:20]
<li>
กระบวนการบูตระบบ (Booting Process) [01:46:42]: อธิบายการทำงานของระบบในการเริ่มเปิดเครื่องและการโหลดระบบปฏิบัติการ (OS) ผ่านกลไกของ BIOS, UEFI และตัวจัดระบบบูตเครื่องอย่าง GRUB [01:47:06] ในกรณีที่เครื่องคอมพิวเตอร์มีการแบ่งพาร์ทิชันเพื่อติดตั้งระบบปฏิบัติการไว้มากกว่าหนึ่งระบบ (Dual OS) ก่อนที่จะส่งคลาสเรียนต่อไปศึกษาเรื่อง Process ในรูปแบบออนไซต์สัปดาห์ถัดไป
</ol>
</details></li>
        </ul>
        <p><b>Linux Tutorial:</b>
        <ul>
          <li>Slide: <a href="Slides/CS222-2026-Lab-01-Basic-Linux.pdf">Basic Linux Tutorial</a>
          <li>Video: <a href="https://youtu.be/l7Rbavlj1SQ">Linux Tutorial 1</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
ประวัติศาสตร์ของ Unix และ Linux [07:39]: ย้อนรอยประวัติศาสตร์การพัฒนาระบบปฏิบัติการ โดยเล่าถึงจุดเริ่มต้นจากศูนย์วิจัย Bell Labs ของบริษัท AT&T [08:20] รวมถึงวิวัฒนาการจากการใช้งานคอมพิวเตอร์ผ่านเครื่องปลายทาง (Terminal) ในอดีต [11:22]
<li>
การใช้งานคำสั่งพื้นฐานและการจัดการสิทธิ์ (Permission) บน Linux [02:44:31]: อธิบายแนวคิดและคำสั่งที่เกี่ยวข้องกับการจัดการสิทธิ์เข้าถึงไฟล์ (File Permissions) สำหรับเจ้าของ (Owner) กลุ่ม (Group) และบุคคลภายนอก (Others) รวมถึงการใช้งานคำสั่ง เช่น umask และการทำ Redirection ก่อนจะทิ้งท้ายให้นักศึกษาไปศึกษาต่อด้วยตนเองเพื่อทำ Assignment [02:45:55]
</ol>
</details></li>
          <li>Video: <a href="https://youtu.be/5dZ6Yz3MKbk">Linux Tutorial 2</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
การจัดการสิทธิ์และผู้ใช้งานบน Linux [06:21]: อธิบายแนวคิดระบบที่รองรับผู้ใช้งานหลายคน (Multi-user) โดยแบ่งประเภทเป็นผู้ใช้ทั่วไปและผู้ดูแลระบบ (Root) [07:17] รวมถึงอธิบายกลไกการป้องและการกำหนดสิทธิ์ (File Permissions) ในการอ่าน เขียน หรือเข้าถึงพื้นที่ของแต่ละคน [08:33]
<li>
การจัดการ Environment Variables และเส้นทางระบบ [01:29:45]: สาธิตวิธีการเพิ่มและแก้ไขตัวแปรสภาพแวดล้อม เช่น การเพิ่ม path หรือ directory ใหม่เข้าไปในตัวแปร $PATH เพื่อเรียกใช้งานคำสั่งอย่างถูกต้อง
<li>
การเตรียมเนื้อหา Shell Script [01:31:21]: เกริ่นนำก่อนพักเบรก 10 นาที เพื่อเตรียมบรรยายต่อในเรื่องการเขียน Shell Script [01:31:41] ซึ่งเป็นส่วนสำคัญที่จะต้องนำไปใช้ทำแบบฝึกหัดและงานมอบหมายต่อไป
</ol>
</details></li>
          <li>Video: <a href="https://youtu.be/K3ijvB9a1Eo">Linux Tutorial 3</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
การเขียนและการรัน Shell Script [00:17]: อธิบายวิธีการนำคำสั่ง Command Line มารวบรวมไว้ในไฟล์เดียวเพื่อรันต่อเนื่องกัน โดยสอนโครงสร้างพื้นฐานอย่างการใช้ Shebang (#!/bin/bash) [01:04] เพื่อระบุตัวรันสคริปต์ และการเปลี่ยนสิทธิ์ (Permission) เพื่อให้ไฟล์สามารถประมวลผลได้ (Executable) [02:33]
<li>
การส่งและการรับพารามิเตอร์ในสคริปต์ [03:19]: สาธิตการส่งค่าอาร์กิวเมนต์เข้าไปใน Shell Script และการอ้างอิงตำแหน่งตัวแปร เช่น $0 แทนชื่อสคริปต์ และ $1 แทนพารามิเตอร์ตัวแรก
<li>
กระบวนการคอมไพล์โปรแกรมภาษา C (C Compiling) [01:00:02]: อธิบายขั้นตอนการแยกไฟล์ซอร์สโค้ดภาษา C (แยกเป็น Main และฟังก์ชันย่อยโดยใช้ extern) เพื่อคอมไพล์ออกมาเป็น Object File หลายๆ ไฟล์ จากนั้นใช้ Linker รวบรวมไฟล์เหล่านั้นเข้าด้วยกันจนได้เป็นไฟล์พร้อมรัน (Executable File) ที่นำไปใช้งานจริง [01:00:44]
<li>
การสรุปภาพรวมภาคปฏิบัติ [01:01:01]: สรุปการใช้คำสั่ง Linux เบื้องต้นทั้งหมดเพื่อปูทางให้นักศึกษานำความรู้ไปใช้ทำ Assignment และประยุกต์ใช้กับระบบ Cloud หรือ Virtual Machine ในอนาคต
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>8</td>
      <td>Lecture 8: แนวคิดและนิยามของ Process ความสัมพันธ์ระหว่าง Parent และ Child Process
        <ul>
          <li>Video: <a href="https://youtu.be/43hzG7P1QOk">Lecture 8</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-05.pdf">Slide 5</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
แนวคิดและนิยามของ Process [03:23]: เริ่มต้นบทเรียนใหม่ในเรื่อง Process Concept โดยอธิบายถึงนิยามและสถานะการทำงานที่เป็นรูปธรรมของโปรแกรมเมื่อถูกนำไปรันในระบบ
<li>
ธรรมชาติของ Algorithm [09:07]: อธิบายลักษณะของอัลกอริทึมที่มีโครงสร้างการทำงานเป็นลำดับขั้นตอน (Sequential) ตามธรรมชาติของระบบคอมพิวเตอร์
<li>
ความสัมพันธ์ระหว่าง Parent และ Child Process [01:45:05]: อธิบายแนวคิดและกฎเกณฑ์การสร้าง Process ใหม่ โดยเปรียบเทียบเป็นกระบวนการของ "พ่อแม่ (Parent)" และ "ลูก (Child)" ซึ่งตัว Parent จะต้องมีกลไกในการรอรับรู้การสิ้นสุดการทำงานของ Child Process [01:46:02] เสมอ เพื่อไม่ให้เกิดผลกระทบต่อระบบโดยรวม (เช่น การเกิด Zombie หรือ Orphan Process) ก่อนจะนัดหมายมาเรียนต่อในเรื่องการใช้ System Call กลุ่ม fork() และ exec() ในครั้งถัดไป [01:46:26]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10, APUE </td>
    </tr>
    <tr>
      <td>9</td>
      <td>Lecture 9: โครงสร้างของ Process ในหน่วยความจำ  วงจรชีวิตและความสัมพันธ์ของ Process
        <ul>
          <li>Video: <a href="https://youtu.be/3hQvEFk0Gt8">Lecture 9</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-05.pdf">Slide 5</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
โครงสร้างของ Process ในหน่วยความจำ [00:19]: ทบทวนส่วนประกอบต่างๆ ของ Process เมื่ออยู่ใน Memory ซึ่งแบ่งเป็นเซกเมนต์ (Segment) ได้แก่ Text (ส่วนที่เก็บโค้ดโปรแกรม ซึ่งระบบจะกำหนดให้เป็นแบบ Read-only เพื่อความปลอดภัยจากการถูกแฮกหรือฝังโค้ดแปลกปลอม), Data, Heap และ Stack [00:48]
<li>
วงจรชีวิตและความสัมพันธ์ของ Process [04:42]: อธิบายเรื่องการเกิดขึ้นและการสิ้นสุดลงของ Process รวมถึงการเชื่อมโยงความสัมพันธ์ในลักษณะของตระกูลลำดับชั้น เช่น Parent และ Child Process [05:13] ซึ่งมีความสำคัญอย่างมากในระบบปฏิบัติการ
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10, APUE </td>
    </tr>
    <tr>
      <td>10</td>
      <td>Lecture 10: สถานะและการทำงานของ Linux Process  กลไกการเกิด Zombie Process
        <ul>
          <li>Video: <a href="https://youtu.be/f6Stb7c4TWU">Lecture 10</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-06.pdf">Slide 6</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
สถานะและการทำงานของ Linux Process [02:43]: ลงลึกเนื้อหาในส่วนของ Linux Process (Part 1) โดยอธิบายถึงวงจรชีวิต (Life Cycle) และเหตุการณ์การเปลี่ยนสถานะต่างๆ [06:13] เช่น สถานะกำลังรัน, สถานะหลับ (Sleeping ซึ่งมีทั้งแบบปลุกได้และห้ามปลุก) [08:42] และสถานะหยุดทำงาน (Stopped)
<li>
กลไกการเกิด Zombie Process [01:22:12]: อธิบายปัญหาการเกิด Zombie Process ในระบบ Linux ซึ่งมักเกิดขึ้นในช่วงเวลาสั้นๆ (Context Switching) ระหว่างที่ Child Process ได้ทำคำสั่ง exit สิ้นสุดลงไปแล้ว แต่ Parent Process ยังไม่ได้เรียกคำสั่ง wait() มาจัดการเคลียร์ข้อมูลของ Child ออกไปจากระบบ [01:22:40] ก่อนที่จะนัดหมายเรียนต่อในเรื่องตัวอย่างการใช้ System Call กลุ่ม fork() และ exec() ในวันศุกร์ถัดไป [01:23:22]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10, APUE </td>
    </tr>
    <tr>
      <td>11</td>
      <td>Lecture 11: การแยกกระบวนการเพื่อความปลอดภัย (Isolation) กลไกการทำงานของ Fork และ Exec System Call  โครงสร้างการทำงานของ Shell Program 
        <ul>
          <li>Video: <a href="https://youtu.be/Z6nw9c7f5Ic">Lecture 11</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-06.pdf">Slide </a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
การแยกกระบวนการเพื่อความปลอดภัย (Isolation) [03:13]: อธิบายว่ากลไกหลักในการรักษาความปลอดภัยของระบบคอมพิวเตอร์คือการแยก Process ออกจากกันอย่างเด็ดขาดผ่านระบบหน่วยความจำเสมือน (Virtual Memory) เพื่อไม่ให้แต่ละโปรแกรมมองเห็นหรือก้าวล่วงข้อมูลของโปรแกรมอื่นหรือตัว OS เอง [05:26] พร้อมยกตัวอย่างช่องโหว่ระดับฮาร์ดแวร์ในอดีตอย่าง Meltdown และ Spectre ที่เคยส่งผลกระทบต่อสถาปัตยกรรม CPU [07:29]
<li>
กลไกการทำงานของ Fork และ Exec System Call [01:11]: ทบทวนการสร้าง Child Process ผ่าน fork() ซึ่งเป็นการจำลองโลกส่วนตัวของกระบวนการแม่ (Parent) ออกมา และการใช้ exec() เพื่อเปลี่ยนการประมวลผลโค้ดตัวเดิมไปรันโปรแกรมตัวใหม่ [07:41]
<li>
โครงสร้างการทำงานของ Shell Program [01:34:24]: สาธิตการเขียนคำสั่งรับคำรับอินพุตผ่าน Loop เพื่อทำความเข้าใจการทำงานเบื้องต้นของโปรแกรมระบบเชลล์ (เช่น การรันคำสั่ง ls) โดยเมื่อมีคำสั่งเข้ามา ระบบจะสร้างกระบวนการลูกขึ้นมาประมวลผลคำสั่งนั้นๆ ในขณะที่กระบวนการแม่จะหยุดรอ (waitpid) จนกว่าลูกจะประมวลผลเสร็จสิ้นจึงจะวนกลับมารับคำสั่งถัดไป [01:35:14] เพื่อเป็นแนวทางสำหรับงานเดี่ยวชิ้นถัดไป (Assignment) และนัดหมายเรียนออนไซต์เพื่อดูเฉลยข้อสอบมิดเทอมในสัปดาห์หน้า [00:27]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10, APUE </td>
    </tr>
    <tr>
      <td>12</td>
      <td>Lecture 12: แนวคิดด้าน Process Scheduling
        <ul>
          <li>Video: <a href="https://youtu.be/ZCfq0YP8CJg">Lecture 12</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-07.pdf">Slide 7</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
การทบทวนข้อสอบมิดเทอมและการเกิด Zombie Process [05:03]: ทบทวนกลไกของโค้ดที่มีการ fork() แตกกระบวนการลูก รวมถึงการอธิบายไดอะแกรมข้อสอบเกี่ยวกับการสิ้นสุดกระบวนการ (exit) และการรอรับข้อมูล (wait) ของ Parent Process ซึ่งความเหลื่อมล้ำทางเวลาของสองเหตุการณ์นี้คือช่องว่างที่ทำให้เกิด Zombie Process [06:56]
<li>
แนวคิดด้าน Process Scheduling Metrics [01:21:31]: เริ่มต้นอธิบายเกณฑ์และมาตรวัดประสิทธิภาพในการจัดตารางเวลาของ Process (Process Scheduling) โดยเน้นอธิบายเรื่อง Response Time (เวลาที่ระบบใช้ตอบสนองจนเกิด Output แรก มักเน้นในกลุ่ม Interactive Process) [01:21:42] และเกริ่นค้างแนวคิดเรื่อง Turnaround Time (เวลารวมทั้งหมดตั้งแต่ Process เข้ามาจนทำงานเสร็จสิ้น) [01:22:48] เพื่อนำไปอธิบายและเคลียร์เนื้อหาต่อในการเรียนออนไลน์วันศุกร์ถัดไป [01:23:13]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10 </td>
    </tr>
    <tr>
      <td>13</td>
      <td>Lecture 13: Process Scheduling และการจัดการตารางเวลาบนระบบหลายประมวลผล (Multiprocessor Scheduling)
        <ul>
          <li>Video: <a href="https://youtu.be/5upbF_YXKlI">Lecture 13</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-07.pdf">Slide 7</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
รายละเอียดโจทย์ใน Assignment 3 [05:25]: อธิบายแนวทางการทำโจทย์ข้อใหญ่ เช่น การเขียนโปรแกรมจำลองการสร้าง Process เป็นทอดๆ (Generation/Recursive Process Creation) ผ่านคำสั่ง fork() [07:54] และการพัฒนาปรับปรุงแก้ไขโปรแกรมระบบเชลล์เบื้องต้น (Shell 1) ให้สามารถรองรับการป้อนพารามิเตอร์ซับซ้อนเพิ่มขึ้นได้ (เช่น ls -l) [08:37]
<li>
การจัดการตารางเวลาบนระบบหลายประมวลผล (Multiprocessor Scheduling) [01:48:57]: บรรยายทฤษฎีการจัดตารางงาน (Scheduling) จากเดิมที่เป็นระบบ CPU คอร์เดียว สู่ระบบคอมพิวเตอร์และมือถือยุคปัจจุบันที่เป็นแบบ Multicore CPU, Hyper-threading, Heterogeneous Multiprocessing และ Numa System [01:49:14] โดยอธิบายหลักการเบื้องต้นของ OS ในการกระจายงานอย่างมีประสิทธิภาพ ก่อนที่จะนัดหมายเรียนออนไลน์ต่อในสัปดาห์หน้า [01:50:25]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10 </td>
    </tr>
    <tr>
      <td>15</td>
      <td>Lecture 14: วิวัฒนาการของ CPU สู่ระบบหลายตัวประมวลผล กลไกการจัดตารางเวลาของ OS บนระบบ Multiprocessor
        <ul>
          <li>Video: <a href="https://youtu.be/iB_FqYcChPE">Lecture 14</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-07.pdf">Slide 7</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
วิวัฒนาการของ CPU สู่ระบบหลายตัวประมวลผล [01:54]: เทียบสถาปัตยกรรม CPU จากยุค 90-2000 ที่เน้นเพิ่มความเร็วคอร์เดียวตามกฎของมัวร์ (Moore's Law) [04:03] มาสู่ระบบในปัจจุบันที่เป็น Multiprocessor และ Multicore (เช่น การต่อขยายผ่าน CPU Socket บนเมนบอร์ด) [05:14] รวมถึงอธิบายคุณสมบัติระบบหน่วยความจำร่วม เช่น UMA (Symmetric Multiprocessing: SMP) ที่ทุก CPU เข้าถึง Memory ด้วยความเร็วเท่ากัน [07:27]
<li>
กลไกการจัดตารางเวลาของ OS บนระบบ Multiprocessor [01:23:56]: บรรยายความท้าทายของ OS ในการทำ Load Balancing และอธิบายเหตุผลที่ระบบปฏิบัติการจะพยายามหลีกเลี่ยงการย้ายโปรเซสข้ามคอร์ (Process Migration) บนระบบ NUMA Node เนื่องจากมีต้นทุน (Cost) สูง ทั้งในแง่การย้ายข้อมูลในหน่วยความจำและปัญหา Cache Miss ที่ต้องล้างแคชเก่าทิ้งเพื่อเริ่มสร้างข้อมูลแคชใหม่ในคอร์ตัวใหม่ [01:24:34] ก่อนจะนัดหมายขึ้นบทเรียนเรื่อง Multithreading ในครั้งถัดไป [01:25:09]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>15</td>
      <td>Lecture 15: แนวคิดเรื่อง Multithreading การบริหารจัดการทรัพยากรร่วมกัน (Resource Sharing) กฎของ Gustafson และแนวคิด Scalability
        <ul>
          <li>Video: <a href="https://youtu.be/VkBZfT7Jv20">Lecture 15</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-08.pdf">Slide 8</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
แนวคิดเรื่อง Multithreading [00:55]: เริ่มต้นบทเรียนใหม่ในเรื่อง Multithreading โดยปูพื้นฐานความแตกต่างระหว่าง Process และ Thread อธิบายถึงเหตุผลในการสร้าง Flow การทำงานหลายๆ Flow ให้ทำงานไปพร้อมกันเพื่อตอบสนองความต้องการของผู้ใช้ [10:05]
<li>
การบริหารจัดการทรัพยากรร่วมกัน (Resource Sharing) [08:41]: บรรยายถึงกลไกและปัญหาเมื่อมีการใช้ทรัพยากรระบบร่วมกัน (Shared Resources) ซึ่งจำเป็นต้องมีระบบการจัดคิว (Queue) และการควบคุมการเข้าถึงที่ยุติธรรม (Fairness) เพื่อไม่ให้เกิดความสับสนหรือข้อมูลขัดแย้งกันในระบบ [09:35]
<li>
กฎของ Gustafson และแนวคิด Scalability [01:47:14]: อธิบายการเปลี่ยนมุมมองเชิงทฤษฎีจาก Amdahl's Law มาสู่ Gustafson's Law [01:47:34] ซึ่งส่งผลให้เกิดแนวคิดเรื่อง Scalability ที่เป็นรากฐานสำคัญในการพัฒนาซูเปอร์คอมพิวเตอร์และระบบ Data Center ขนาดใหญ่ที่มีหน่วยประมวลผลทำงานร่วมกันนับแสนตัวในปัจจุบัน [01:48:03] ก่อนจะนัดหมายสรุปเนื้อหา Thread Programming ในวันพุธถัดไป [01:48:34]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10, APUE, OSTEP </td>
    </tr>
    <tr>
      <td>16</td>
      <td>Lecture 16: การคำนวณประสิทธิภาพด้วย Amdahl's Law  ธรรมชาติของ Concurrent Programming
        <ul>
          <li>Video: <a href="https://youtu.be/h4HysTgfx0w">Lecture 16</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-08.pdf">Slide 8</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
การคำนวณประสิทธิภาพด้วย Amdahl's Law [00:13]: ทบทวนและอธิบายรายละเอียดของ Amdahl's Law ซึ่งเป็นกฎที่ใช้วัดประสิทธิภาพความเร็วรวมของระบบ (Speedup) เมื่อมีการเพิ่มจำนวนหน่วยประมวลผล ($N$) เข้ามาช่วยรันงานแบบขนาน โดยระบุว่าความเร็วที่เพิ่มขึ้นจะถูกจำกัดด้วยสัดส่วนของงานส่วนที่ไม่สามารถแยกทำแบบขนานได้ หรือส่วนที่เป็นลำดับ (Serial fraction: $S$) [02:55] ซึ่งต่อให้เพิ่ม CPU มากจนเป็นอนันต์ ความเร็วสูงสุดที่จะได้ก็จะไม่มีทางเกิน $1/S$ [07:51]
<li>
ธรรมชาติของ Concurrent Programming [01:22:53]: บรรยายถึงพฤติกรรมการทำงานของระบบ Multi-programming และการรันโปรแกรมแบบหลายเทรดพร้อมกัน (Concurrent Programming) โดยชี้ให้เห็นว่าลำดับความเร็วและเวลาในการประมวลผลของแต่ละเทรดจะไม่มีความแน่นอน (Non-deterministic) เนื่องจากปัจจัยแวดล้อมระบบ เช่น การทำ Context switching หรือการโดนโปรแกรมอื่นแย่งใช้ CPU [01:23:19]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10 </td>
    </tr>
    <tr>
      <td>16.5</td>
      <td>Lecture 16.5: แนวคิดเรื่อง Scalability ของระบบคอมพิวเตอร์ สรุปภาพรวมพื้นฐานสำคัญของระบบ Multicore และการเขียนโปรแกรมแบบ Multithreading  
        <ul>
          <li>Video: <a href="https://youtu.be/t2ZuvUxcjWE">Lecture 16.5</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-08.pdf">Slide 8</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
แนวคิดเรื่อง Scalability ของระบบคอมพิวเตอร์ [03:50]: บรรยายความหมายของ Scalability (ความสามารถในการขยายระบบ) ทั้งในแง่ซอฟต์แวร์และฮาร์ดแวร์ โดยอธิบายว่าระบบที่รองรับการปรับขยายที่ดี คือระบบที่เมื่อเราเพิ่มทรัพยากร (เช่น CPU หรือ Storage) เข้าไปแล้ว ระบบยังสามารถคงประสิทธิภาพการทำงาน (Efficiency) ไว้ได้ดีใกล้เคียงเดิม [05:29] พร้อมยกตัวอย่างระบบ DNS (Domain Name System) ว่าเป็นหนึ่งในระบบฐานข้อมูลที่ Scalable ที่สุดในโลกอินเทอร์เน็ต [08:02]
<li>
การสรุปท้ายคาบและหัวข้อถัดไป [01:27:34]: สรุปภาพรวมพื้นฐานสำคัญของระบบ Multicore และการเขียนโปรแกรมแบบ Multithreading [01:28:36] ก่อนจะประกาศปิดท้ายบทเรียนเรื่อง Thread ไว้เพียงเท่านี้ โดยนัดหมายขึ้นบทเรียนถัดไปเกี่ยวกับเรื่องหน่วยความจำ (Memory Management) รวมถึงอาจมี Assignment ให้ไปศึกษาเพิ่มเติมด้วยตัวเองในครั้งหน้า [01:28:52]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10, OSTEP </td>
    </tr>
    <tr>
      <td>17</td>
      <td>Lecture 17: การต่อยอดเนื้อหาเรื่อง Synchronization แนวคิดเรื่อง Critical Section และกลไกควบคุมการเข้าถึง เครื่องมือทำ Thread Synchronization ในระบบ Linux 
        <ul>
          <li>Video: <a href="https://youtu.be/w1TyiPafU2w">Lecture 17</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-09.pdf">Slide 9</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
การต่อยอดเนื้อหาเรื่อง Synchronization [00:02]: แม้ตอนแรกจะแพลนสอนเรื่อง Memory แต่แกนหลักในคาบนี้ถูกปรับมาอธิบายเรื่องการทำงานประสานกัน (Synchronization) เพิ่มเติมเพื่อให้เนื้อหาครบถ้วนสมบูรณ์ [00:22] พร้อมแนะแนวทางทำ Assignment และให้วิดีโอศึกษาเพิ่ม [06:44]
<li>
แนวคิดเรื่อง Critical Section และกลไกควบคุมการเข้าถึง [07:09]: อธิบายแนวคิด Critical Section (พื้นที่วิกฤต) โดยเปรียบเทียบเชิงอุปมาอุปไมยในชีวิตประจำวัน เช่น ห้องที่เข้าใช้ได้ทีละคนและต้องล็อกกุญแจ (Mutex Lock) [08:41] หรือการจัดการคิวของลูกค้าในร้านอาหาร [09:58] เพื่อแสดงถึงกระบวนการป้องกันไม่ให้หลายเทรดเข้าถึงทรัพยากรร่วมกันในเวลาเดียวกัน
<li>
เครื่องมือทำ Thread Synchronization ในระบบ Linux [01:53:31]: แนะนำเครื่องมือระดับสูงอย่าง pthread_barrier (กลไกการรอให้ทุกเทรดทำงานมาถึงจุดที่กำหนดพร้อมกันก่อนจะปล่อยให้ไปต่อ) [01:53:36] และอธิบายสถาปัตยกรรมเบื้องหลังการทำงานของ Mutex ใน Linux เช่น กลไก Futex, Spin Lock, และคำสั่งระดับฮาร์ดแวร์ Test-and-Set [01:54:36] ก่อนที่จะประกาศจบบทเรียน Synchronization เพื่อเตรียมขึ้นเนื้อหา Memory Management ในคาบหน้า [01:54:51]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10:, APUE, OSTEP </td>
    </tr>
    <tr>
      <td>18 - 19</td>
      <td>Lecture 18 - 19: กลไกหน่วยความจำและ Dynamic Linking 
        <ul>
          <li>Video: <a href="https://youtu.be/KOvJGrTyBbw">Lecture 18 - 19</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-10.pdf">Slide </a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
ความสำคัญและการทำงานของ ECC Memory ใน Server [00:43]: อธิบายถึง ECC Memory (Error-Correcting Code) ซึ่งมีความจำเป็นอย่างยิ่งสำหรับเครื่อง Server หรือระบบที่ต้องเปิดทำงานตลอด 24 ชั่วโมงใน Data Center [09:45] โดยทำหน้าที่ตรวจสอบและกู้คืนความเสียหายจากข้อผิดพลาดในระดับบิตที่เรียกว่า Bit Flip ซึ่งมักเกิดขึ้นได้เมื่อเปิดเครื่องไว้นานๆ หรือจากผลกระทบของรังสีคอสมิก (Cosmic Rays) ในชั้นบรรยากาศ [03:40], [06:04]
<li>
กลไกหน่วยความจำและ Dynamic Linking [10:03]: บรรยายการจัดการหน่วยความจำฝั่งซอฟต์แวร์ตามสถาปัตยกรรมแบบ Von Neumann พร้อมอธิบายกลไก Dynamic Linking ซึ่งเป็นการจัดการของ OS ที่ทำงานร่วมกับฮาร์ดแวร์หน่วยความจำ (MMU) เพื่อแชร์ไลบรารีหรือรูทีนชุดเดียวกันระหว่างโปรเซสต่างๆ (เช่น โปรเซส 1 และ 2) ได้ โดยโปรแกรมสามารถเรียกใช้และมองเห็นผ่านระบบหน่วยความจำเสมือน (Virtual Memory) ได้ทันทีโดยไม่จำเป็นต้องโหลดซ้ำซ้อน [01:52:50] ก่อนที่จะนัดหมายเรียนต่อในสัปดาห์ถัดไป [01:54:11]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10 </td>
    </tr>
    <tr>
      <td>20</td>
      <td>Lecture 20: การตรวจสอบ Memory Segment ของโปรแกรม การใช้เทคนิค ASID ในระบบ Paging 
        <ul>
          <li>Video: <a href="https://youtu.be/O6w9CMbrdG8">Lecture 20</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-10.pdf">Slide 10</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
กำหนดการและคำแนะนำเรื่อง Soft Skills [00:17]: แจ้งงดคลาสในวันศุกร์ถัดไปช่วงเทศกาลสงกรานต์ [00:35] ชี้แจงเกี่ยวกับ Assignment เรื่อง Thread [00:40] พร้อมทั้งสอดแทรกความสำคัญของ Soft Skills เช่น Emotional Intelligence (ความฉลาดทางอารมณ์) ที่จำเป็นอย่างมากเมื่อต้องออกไปทำงานร่วมกับผู้อื่นในองค์กร [00:53]
<li>
การตรวจสอบ Memory Segment ของโปรแกรม [03:21]: บรรยายการจัดการหน่วยความจำฝั่งซอฟต์แวร์ แนะนำการใช้คำสั่งระดับยูทิลิตี เช่น size เพื่อแจงข้อมูลของ Executable Program ออกเป็น Code (Text) Segment และ Data Segment [05:26] รวมถึงการใช้ pmap (Memory Map) เพื่อส่องดูโครงสร้าง Virtual Memory Space ของแต่ละโปรเซสในขณะที่ทำงานอยู่ [07:26]
<li>
การใช้เทคนิค ASID ในระบบ Paging [01:23:22]: อธิบายกลไก ASID (Address Space Identifier) ซึ่งเป็นหมายเลขเฉพาะที่ OS กำหนดให้แต่ละโปรเซสที่กำลังรัน เพื่อใช้จับคู่กับตัวเลข Logical Page ภายในแคชฮาร์ดแวร์ TLB (Translation Lookaside Buffer) [01:24:05] ทำให้ระบบสามารถคงข้อมูลการแปลแอดเดรสของหลายๆ โปรเซสไว้ใน TLB พร้อมกันได้โดยไม่ต้องล้างแคชทิ้ง (Flush) ทุกครั้งเมื่อเกิด Context Switch ส่งผลให้ระบบทำงานได้รวดเร็วและมีประสิทธิภาพสูง [01:24:17] ก่อนที่จะนัดหมายเรียนเรื่อง Hierarchical Page Table บนสถาปัตยกรรมแบบ 64 บิต ในวันศุกร์ถัดไป [01:24:27]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>21</td>
      <td>Lecture 21: กลไกการแปลแอดเดรสหน่วยความจำ (Address Translation) 
        <ul>
          <li>Video: <a href="https://youtu.be/9i5cLPTNZAI">Lecture 21</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-10.pdf">Slide 10</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
กลไกการแปลแอดเดรสหน่วยความจำ (Address Translation) [00:12]: บรรยายการเข้าถึงหน่วยความจำเสมือน (Virtual Memory) ของ CPU โดยหน่วยจัดการหน่วยความจำ (MMU) จะดึงพิกัดตำแหน่งตารางหน้าของแต่ละโปรเซสจาก CR3 Register [01:23] เพื่อนำ Logical Page Number ไปแปลค่าผ่าน Page Table และฮาร์ดแวร์แคชเพื่อแปลงเป็น Physical Address ก่อนเก็บข้อมูลไว้ใน Cache ระดับต่างๆ [03:34], [05:36]
<li>
ความแตกต่างของการจัดการระบบ Paging บนคอมพิวเตอร์และมือถือ [01:35:14]: เปรียบเทียบกระบวนการทำ Paging บนสถาปัตยกรรมระบบเครื่อง Server ทั่วไปที่มีพื้นที่หน่วยความจำสำรอง (Swap Area) สำหรับดึงหน้าข้อมูลเข้า-ออก (Page In / Page Out) [01:35:26] กับระบบปฏิบัติการบนมือถือ (เช่น iOS) ที่มักจะไม่ใช้ระบบ Swap เนื่องจากความล่าช้าในการอ่านเขียนข้อมูล แต่จะใช้วิธี Terminate หรือสั่งปิดแอปพลิเคชันนั้นทิ้งทันทีหากหน่วยความจำระบบไม่พอ [01:35:53]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>22</td>
      <td>Lecture 22: ระบบหน่วยความจำเสมือน (Virtual Memory)  อัลกอริทึมทดแทนหน้าหน่วยความจำ 
        <ul>
          <li>Video: <a href="https://youtu.be/fYXKSLTlVaI">Lecture 22</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-11.pdf">Slide 11</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
การก้าวสู่ระบบหน่วยความจำเสมือน (Virtual Memory) [00:11]: บรรยายถึงวิวัฒนาการและประวัติศาสตร์ของระบบหน่วยความจำเสมือน (Virtual Memory) [02:07] ที่พัฒนาควบคู่มากับไมโครโพรเซสเซอร์ [06:10] เพื่อเปลี่ยนผ่านจากระบบ Physical Memory ในยุคโบราณ ช่วยให้คอมพิวเตอร์เครื่องเดียวสามารถจัดสรรโลกเสมือนแยกเฉพาะให้แต่ละโปรแกรมรันได้พร้อมกันอย่างปลอดภัยใน Time Slide ของตนเอง [05:59], [07:41] โดยในคาบนี้เน้นสอนเรื่อง Demand Paging, Copy-on-Write, Page Replacement และ Thrashing [00:55]
<li>
กลไกการทำงานของระบบหน่วยความจำเสมือน [09:25]: อธิบายการตัดแบ่งโปรแกรมออกเป็นหน้าๆ เรียกว่า Page เพื่อโหลดเฉพาะหน้าที่จำเป็นต้องใช้งานเข้าสู่ Physical Memory โดยระบบปฏิบัติการและฮาร์ดแวร์จะร่วมมือกันควบคุมผ่านแนวคิด Demand Paging [09:40]
<li>
อัลกอริทึมทดแทนหน้าหน่วยความจำ (Second-Chance / Clock Algorithm) [01:54:10]: อธิบายตัวอย่างการทำงานและตรรกะของ Second-Chance (Clock) Algorithm ซึ่งใช้โครงสร้าง Circular Queue ร่วมกับตัวชี้ (Pointer) และ Reference Bit เพื่อไล่ตรวจสอบและเปลี่ยนบิตจาก 1 เป็น 0 สำหรับให้โอกาสที่สองแก่หน้าที่พึ่งถูกอ้างอิง ก่อนจะมองหาหน้าที่มีบิตเป็น 0 เพื่อเลือกเป็น Victim Frame สำหรับสลับออก (Page Out) [01:54:30] ก่อนนัดหมายขึ้นเรื่อง Enhanced Second-Chance และปิดท้ายบทเรียนในวันศุกร์ถัดไป [01:55:04]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10 </td>
    </tr>
    <tr>
      <td>23</td>
      <td>Lecture 23: อัลกอริทึมทดแทนหน้าหน่วยความจำ (Page Replacement)    User memory space/Kernel memory space    กลไกความปลอดภัย KPTI (Kernel Page Table Isolation)
        <ul>
          <li>Video: <a href="https://youtu.be/e234Enmu2fg">Lecture 23</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-11.pdf">Slide 11</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-12.pdf">Slide 12</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
อัลกอริทึมทดแทนหน้าหน่วยความจำ (Page Replacement) [01:25]: อธิบายและต่อยอดกลไกแบบ Second-Chance (Clock) Algorithm [06:15] ไปสู่ Enhanced Second-Chance Algorithm โดยเพิ่มการพิจารณาบิตตรวจสอบอีกหนึ่งตัวคือ Modify Bit (หรือ Dirty Bit) ควบคู่ไปกับ Reference Bit เพื่อใช้แยกประเภทความสำคัญของข้อมูล [04:20] และทำให้ระบบเลือกเหยื่อ (Victim Frame) มาทดแทนได้อย่างฉลาดขึ้นโดยเลี่ยงการเลือกหน้าที่มีการแก้ไขเพื่อลดภาระการเขียนข้อมูลกลับลงดิสก์ [07:02]
<li>
กลไกความปลอดภัย KPTI (Kernel Page Table Isolation) [02:06:31]: อธิบายแนวคิดและโครงสร้างของกลไกความปลอดภัย KPTI เพื่อแยกพื้นที่ทำงานระหว่าง Kernel Space และ User Space ออกจากกันอย่างเด็ดขาด ป้องกันไม่ให้แอปพลิเคชันทั่วไปใน User Mode เข้าถึงหรือมองเห็นโครงสร้างหลักในฝั่ง Kernel [02:06:45] แต่ยังคงเหลือแอดเดรสไว้ส่วนน้อยเท่าที่จำเป็นสำหรับการรันคำสั่ง System Call [02:07:10] ก่อนที่จะนัดหมายสอนเรื่อง Dynamic Memory Allocation, Disk Storage และเทคโนโลยี RAID เพื่อเตรียมปิดคอร์สในสัปดาห์หน้า [02:07:53]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10: </td>
    </tr>
    <tr>
      <td>24</td>
      <td>Lecture 24: Dynamic Memory Allocation โครงสร้างการจัดเก็บข้อมูล และสถาปัตยกรรม RAID
        <ul>
          <li>Video: <a href="https://youtu.be/OPsTUdKcgJ4">Lecture 24</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-12.pdf">Slide 12</a></li>
          <li>Slide: <a href="Slides/CS222-2026-Slide-13.pdf">Slide 13</a></li>
          <li>
<details>
<summary>สรุป</summary>
<ol>
<li>
Dynamic Memory Allocation (Heap & Library API) [02:15]: บรรยายกลไกการจัดสรรหน่วยความจำแบบไดนามิกในภาษา C อธิบายโครงสร้างของ Heap Segment และ Stack Segment [06:35] โดยชี้ให้เห็นว่าการเรียกใช้ฟังก์ชันการจัดสรรหน่วยความจำ (เช่น malloc) เป็นการทำงานผ่าน Library API ที่ตัว Memory Allocator เป็นผู้บริหารจัดการพื้นที่ Heap ไม่ใช่ระบบ System Call โดยตรง [08:29]
<li>
โครงสร้างการจัดเก็บข้อมูลและสถาปัตยกรรม RAID 5 [01:46:06]: ปิดท้ายบทเรียนด้วยเรื่องอาร์เรย์ของดิสก์อิสระหรือ RAID 5 (Distributed Parity) โดยอธิบายกลไกการกระจายข้อมูลและบล็อก Parity สลับกันไปในแต่ละดิสก์ ซึ่งช่วยลดปัญหาคอขวดของการเขียนข้อมูลระบบ Parity และช่วยเพิ่มประสิทธิภาพในการอ่านเขียนข้อมูลแบบขนาน (Parallel) ได้ดียิ่งขึ้น [01:47:14] ก่อนประกาศปิดคอร์สเรียนอย่างเป็นทางการ [01:47:35]
</ol>
</details></li>
        </ul>
      </td>
      <td>OSC10, OSTEP </td>
    </tr>
  </tbody>
</table>
</p>
<p>
  <b>Assignments:</b> 
<table>
  <thead>
    <tr>
      <th>ครั้งที่</th>
      <th>เรื่อง</th>
      <th>อ้างอิง</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>  
        <ul>
          <li>ติดตั้ง Ubuntu Server Linux สองแบบ
          <li>Description: <a href="Assignments/CS222-Assignment-1.pdf">Assign 1</a></li>
        </ul>
      </td>
      <td>TBA </td>
    </tr>
    <tr>
      <td>2</td>
      <td>  
        <ul>
          <li>ฝึกใช้งาน Ubuntu Linux + ศึกษาด้วยตนเอง
          <li>Description: <a href="Assignments/CS222-Assignment-2.pdf">Assign 2</a></li>
        </ul>
      </td>
      <td>TBA </td>
    </tr>
    <tr>
      <td>3</td>
      <td>  
        <ul>
          <li>เรียนรู้ Process
          <li>Description: <a href="Assignments/CS222-Assignment-3.pdf">Assign 3</a></li>
        </ul>
      </td>
      <td>TBA </td>
    </tr>
    <tr>
      <td>4</td>
      <td>  
        <ul>
          <li>เรียนรู้ Pthread Programming Part 1
          <li>Description: <a href="Assignments/CS222-Assignment-4.pdf">Assign 4</a></li>
        </ul>
      </td>
      <td>TBA </td>
    </tr>
    <tr>
      <td>5</td>
      <td>  
        <ul>
          <li>เรียนรู้ pthread part 2 (Synchronization)
          <li>Description: <a href="Assignments/CS222-Assignment-5.pdf">Assign 5</a></li>
        </ul>
      </td>
      <td>TBA </td>
    </tr>
    <tr>
      <td>6</td>
      <td>  
        <ul>
          <li>เรียนรู้ Dynamic Memory Allocation และทบทวน RAID
          <li>Description: <a href="Assignments/CS222-Assignment-6.pdf">Assign 6</a></li>
        </ul>
      </td>
      <td>TBA </td>
    </tr>
  </tbody>
</table>
</p>
  
