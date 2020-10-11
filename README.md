# Smart__Building
# WpfMonitoringProgram
Arduino Photo Interrupt 센서 값 수집 프로그램
> 1. LiveChart를 통해 Value 출력한다.
> 2. Simulation(난수 생성) 값을 출력으로 설정
> 3. Arduino로 부터 Value 입력 후 출력으로 설정
****
>#메인뷰 동작
****
###### 메인 뷰 화면
![메인 뷰](/readmeFile/MainView.PNG)
###### 메뉴 바의 도움말-정보를 통해 AssemblyInfo의 정보를 얻을 수 있다.
![메인 뷰 메뉴 바](/readmeFile/ThisProgramViewMenuBar.PNG)
###### Dialog로 화면 출력
![프로그램 뷰](/readmeFile/ThisProgramView.PNG)
****
>#시뮬레이션 동작
****
###### 난수를 사용하여 값을 전송하여 화면에 출력하는 동작
###### 시뮬레이션-시작 또는 화면 하단의 Start 버튼을 통해 시뮬레이션 동작 수행 가능
![시뮬레이션 메뉴 바](/readmeFile/SimulationMenuBar.PNG)
###### 초 단위로 난수로 생성된 값이 LiveChart를 통해 출력
###### 시뮬레이션 동작 중에는 초록색으로 출력됨
![시뮬레이션 시작](/readmeFile/SimulationStart.PNG)
###### Stop 또는 시뮬레이션-종료 버튼을 통해 시뮬레이션 정지
![시뮬레이션 종료](/readmeFile/SimulationStop.PNG)
###### 가장 최근의 5개의 값만 출력하도록 확대/축소 버튼을 통해 조작 가능 
![줌인, 줌아웃 토글](/readmeFile/SimulationZoomIn.PNG)
****
>#아두이노 포트
****
###### 아두이노가 연결된 포트번호를 확인할 수 있다.
![포트목록1](/readmeFile/PortListNone.PNG)
###### 버튼을 클릭하면 포트번호 목록을 탐색한다.
![포트목록탐색](/readmeFile/PortListReset.PNG)
###### 연결된 포트번호를 확인할 수 있다.
![포트목록2](/readmeFile/PortListNew.PNG)
****
>#데이터베이스 활용
****
###### 데이터베이스에 시뮬레이션 결과 값을 저장
![데이터베이스저장](/readmeFile/DBDATA.PNG)
