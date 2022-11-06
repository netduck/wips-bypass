<div align="center">
  <h1>Drivers for Wireless IPS Bypass</h1>
  <h3><b>⚠ 해당 드라이버를 사용하여 발생하는 모든 책임은 사용자에게 있습니다.</b></h3><br/>
  <img src="https://user-images.githubusercontent.com/75542499/200166288-5473e577-dc9c-4f17-b764-689be0273080.png" width="20%"/><br/><br/><br/>
  <p>드라이버 코드 수정을 통해 Dot11 Dos(Denial of Service) 공격을 방어합니다.</p>
  <h2>Defensible attacks</h2>
  <img src="https://user-images.githubusercontent.com/75542499/200167352-00f7ee95-3175-4b9d-a86c-89f54a12c216.png" width="10%"/>
  <h3>Channel Switch Anouncement attack using beacons</h3>
  <h3>Deauthentication attack to STA</h3>
  <h2>Drivers</h2>
  <h3><a href="https://github.com/netduck/wips-bypass/tree/main/rtl8812au">RTL8812AU/21AU & RTL8814AU</a></h3>
  <h3>How to install</h3>
  <p>해당 드라이버는 DKMS를 활용하여 설치할 수 있습니다.</p>
    <code>$ sudo apt-get install dkms</code>
    <br/>
  <h4>Installation of driver</h4>
  <p>소스 코드 디렉터리에서 다음과 같은 명령어를 실행시켜 드라이버를 설치해줍니다.</p>
    <code>$ sudo make dkms_install</code>
    <br/>
  <h4>Removal of driver</h4>
  <p>소스 코드 디렉터리에서 다음과 같은 명령을 통해 설치한 드라이버를 제거할 수 있습니다.</p>
    <code>$ sudo make dkms_remove</code>
  <h4>Make</h4>
  <p>또한 make 명령을 통해 다음과 같이 설치할 수 있습니다.</p>
    <code>$ make && make install</code>
</div>
