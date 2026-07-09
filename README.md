# Label Print Desktop

Windows 설치형 Label Print 데스크톱 앱 **릴리스 저장소**입니다.

- **공식 다운로드:** https://label.youjion.com/download
- **소스 개발:** https://github.com/minbokang/label_print (`desktop/`)

## 설치

[Releases](https://github.com/minbokang/desktop_label_print/releases)에서 `LabelPrint-Setup-*.exe`를 받아 설치하세요.

- 운영 콘솔: **https://label.youjion.com**
- Windows 10 이상 (64-bit)

## 이미 설치했는데 개발 서버로 접속되나요?

**2026-07-09 이전**에 받은 `0.1.0` 설치본은 **개발 서버**로 열릴 수 있습니다. 재설치 없이 아래 설정 파일로 운영 서버에 연결할 수 있습니다.

### 방법 1: 설정 파일 (권장)

1. [Releases](https://github.com/minbokang/desktop_label_print/releases/latest)에서 **`label-print-desktop.config.json`** 을 다운로드합니다.  
   (또는 https://label.youjion.com/downloads/label-print-desktop.config.json )
2. 파일 이름이 `label-print-desktop.config.json` 인지 확인합니다.
3. `Label Print Desktop.exe`가 있는 **설치 폴더**에 복사합니다.  
   보통 `%LOCALAPPDATA%\Programs\label-print-desktop\`
4. 앱을 완전히 종료한 뒤 다시 실행합니다.

설정 파일 내용:

```json
{
  "apiBaseUrl": "https://label.youjion.com",
  "startPath": "/login"
}
```

### 방법 2: 최신 설치본 재설치

Releases에서 최신 `LabelPrint-Setup-*.exe`를 다시 받아 설치하면 운영 서버가 기본값입니다.

## 릴리스 파일

| 파일 | 설명 |
|------|------|
| `LabelPrint-Setup-*.exe` | Windows 설치 프로그램 |
| `label-print-desktop.config.json` | 예전 설치본용 운영 서버 URL 설정 (선택) |

## 문의

Label Print 공식 사이트: https://label.youjion.com
