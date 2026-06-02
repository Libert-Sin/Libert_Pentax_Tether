# Libert Pentax Tether

A clean, Java-based lightweight USB tethering tool for PENTAX cameras, developed by **Libert Sin** using the official RICOH Camera SDK. 
리코 공식 SDK를 기반으로 자바 환경에서 구동되는 깔끔하고 직관적인 펜탁스 전용 USB 테더링 프로그램입니다.

---

## 🔍 Overview / 소개
Many open-source tethering tools for Pentax have complex and engineering-heavy UIs. **Libert Pentax Tether** provides a highly clean, minimal, and intuitive interface that lets you focus strictly on your shooting. It supports remote shutter release, exposure adjustments, and automatic file transfers.

기존의 펜탁스용 테더링 프로그램들과 달리, 직관적이고 깔끔한 UI를 제공하여 스튜디오 및 모니터링 환경에서 촬영에만 집중할 수 있도록 도와줍니다. 셔터스피드, 조리개, ISO 등의 카메라 원격 제어 및 자동 이미지 전송을 지원합니다.

---

## 🛠️ Key Features / 주요 기능
* **Camera Control**: Remote adjustment of Shutter Speed, Aperture, and ISO via drop-down menus. (드롭박스를 통한 셔터스피드, 조리개, ISO 감도 원격 제어)
* **Format & Focus**: Toggle RAW/JPG storage formats and enable/disable AF before shooting. (RAW/JPG 저장 포맷 선택 및 촬영 전 자동 초점(AF) 활성화 옵션)
* **Battery Monitoring**: Intuitive color-coded battery status indicator (Green/Yellow/Red/White) with precise percentage on hover. (배터리 상태를 색상으로 표시 및 마우스 오버 시 정확한 잔량 확인 가능)
* **Auto-Sorting**: Automatically creates sub-folders based on the shooting date inside your chosen save path. (설정된 저장 위치에 촬영 일자별로 폴더를 자동 생성하여 이미지 저장)

---

## 📷 Supported Cameras / 지원 기종
This tool is built on the official **RICOH Camera SDK**, which means legacy Pentax models without SDK support are not compatible.
* **PENTAX K-1**
* **PENTAX K-1 Mark II**
* **PENTAX KP**
* **PENTAX 645Z**

> 💡 *Note for legacy models: If your camera is not listed above, please consider using [pkTriggerCord](https://melda.info) as an alternative.*

---

## 💻 Supported OS / 지원 운영체제
* **Windows**: Windows 7 / 10 / 11
* **macOS**: High Sierra (10.13) or higher
* **Linux**: Kernel 4.4 or higher (Officially tested on Ubuntu 16.04 / Arch Linux)

---

## 🚀 How to Use / 설치 및 사용 방법

### 1. Requirements (사전 준비)
* You must install the **Java Runtime Environment (JRE)** on your computer.
* 컴퓨터 운영체제에 맞는 자바 런타임(JRE) 설치가 필요합니다.
* 👉 [Download Java (자바 다운로드)](https://java.com)

### 2. Camera Setup (카메라 설정)
1. In your Pentax camera menu, change the **USB Connection (USB 접속)** mode to **PTP**. (카메라 메뉴에서 USB 접속 모드를 **PTP**로 설정합니다.)
2. Connect your camera to the computer using a USB cable. (카메라와 컴퓨터를 USB 케이블로 연결합니다.)
3. Verify that **`PTP`** (looks like `PcP`) is displayed on the camera's top LCD status screen. (카메라 상단 상태창에 PTP 문구가 뜨는지 확인합니다.)

### 3. Running the Program (프로그램 실행)
1. Download and extract the application zip file. (배포된 압축 파일을 다운로드하고 해제합니다.)
2. Run the `LibertPentaxTether_X.Xv.jar` file. (폴더 내의 JAR 파일을 실행합니다.)
   * **macOS**: Right-click the `.jar` file ➔ `Open With` ➔ Select **Jar Launcher**. (맥의 경우 우클릭 후 '다음으로 열기'에서 Jar Launcher를 선택하세요.)
   * **Linux**: Open terminal and run: `java -jar "/PATH/LibertPentaxTether_X.Xv.jar"` (리눅스는 터미널 명령어로 실행합니다.)
3. Click the **Connect (연결)** button to open the main interface. (연결 버튼을 누르면 메인 제어 화면이 나타납니다.)

⚠️ **Known Bug (macOS)**: There is a known path-saving issue on macOS. Images will be saved directly into the folder where your `LibertPentaxTether_X.Xv.jar` file is located, regardless of your chosen directory. (현재 맥 OS 환경에서는 저장위치 설정 버그가 있어, 파일이 있는 폴더에 이미지가 강제 저장되니 실행 전 폴더 위치를 확인해 주세요.)

---

## ✉️ Contact & Support / 문의
If you encounter any issues or want to share test results for untested environments, please contact the developer:
실행 가능 여부 피드백이나 오류 보고는 아래 개발자 블로그 또는 이메일로 전달해 주세요.

* **Developer Official Website**: [Libert Photography](https://www.photoguraphy.com/?page_id=3943)
* **Email**: libert@photoguraphy.com
