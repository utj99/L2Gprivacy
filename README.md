<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>개인정보처리방침 - 음력 생일을 구글 캘린더에 추가하기</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; max-width: 800px; margin: auto; }
        h1, h2, h3 { color: #333; }
        .footer { margin-top: 50px; border-top: 1px solid #eee; padding-top: 20px; font-size: 0.9em; text-align: center; }
        .footer a { margin: 0 10px; text-decoration: none; color: #007bff; }
    </style>
</head>
<body>
    <h1>개인정보처리방침</h1>
    <p><strong>음력 생일을 구글 캘린더에 추가하기 (Lunar2GoogleCalender)</strong></p>
    <p><strong>개발자:</strong> utj99</p>
    <p><strong>연락처:</strong> <a href="utj440077@google.com">utj440077@google.com</a></p>
    <p><strong>발효일:</strong> 2025.05.22</p>

    <p>본 개인정보처리방침은 크롬 확장 프로그램 "음력 생일을 구글 캘린더에 추가하기"(이하 "확장 프로그램")가 사용자 데이터를 어떻게 수집, 사용, 공유, 보호하는지 설명합니다.</p>

    <h2>1. 수집하는 정보</h2>
    <h3>1.1 Google 사용자 데이터 (Google Calendar API를 통한 접근)</h3>
    <p>본 확장 프로그램은 사용자의 동의를 받아 Google Calendar API를 통해 <strong>사용자의 Google 캘린더에 이벤트(음력 생일)를 추가하고 관리하는 데 필요한 최소한의 권한</strong>을 요청합니다. 이 과정에서 <code>https://www.googleapis.com/auth/calendar.events</code> 스코프를 사용합니다.</p>
    <p>확장 프로그램은 사용자의 캘린더에 있는 기존 이벤트 내용을 읽거나, 사용자의 캘린더 데이터를 개발자 서버로 전송하거나, 다른 목적으로 데이터를 수집/저장/분석하지 않습니다. 오직 사용자가 입력한 음력 생일 정보를 양력으로 변환하여 사용자의 캘린더에 새 이벤트를 생성하는 기능만을 수행합니다.</p>
    <p>본 확장 프로그램은 Google API 서비스 사용자 데이터 정책(Google API Services User Data Policy)의 제한적 사용 요건(Limited Use requirements)을 준수합니다.</p>

    <h3>1.2 로컬 저장 데이터 (Local Storage)</h3>
    <p>본 확장 프로그램은 사용자의 편의를 위해 사용자가 입력한 음력 월, 일, 이벤트 이름 및 음력-양력 변환 결과를 사용자 브라우저의 로컬 저장소(<code>chrome.storage.local</code>)에 저장합니다. 이 데이터는 <strong>사용자 기기에만 저장되며, 개발자나 제3자 서버로 전송되거나 공유되지 않습니다.</strong></p>
    <p>이 로컬 데이터는 사용자가 확장 프로그램을 제거하면 자동으로 삭제됩니다.</p>

    <h3>1.3 개인 식별 정보(PII) 수집 여부</h3>
    <p>본 확장 프로그램은 사용자로부터 직접적인 개인 식별 정보(예: 이름, 이메일 주소, 전화번호 등)를 수집하거나 저장하지 않습니다.</p>

    <h2>2. 정보의 사용 목적</h2>
    <p>수집되는(접근되는) 모든 정보는 오직 본 확장 프로그램의 핵심 기능인 <strong>음력 생일을 사용자의 Google 캘린더에 추가하고 관리하는 목적</strong>으로만 사용됩니다.</p>
    <p>어떠한 정보도 마케팅, 광고, 프로파일링 또는 제3자 판매 목적으로 사용되거나 공유되지 않습니다.</p>

    <h2>3. 정보의 공유</h2>
    <p>본 확장 프로그램은 어떠한 사용자 정보도 제3자와 공유하거나 판매하지 않습니다.</p>
    <p>법률이 요구하거나 권리를 보호하기 위해 필요한 경우를 제외하고는 사용자 정보를 공개하지 않습니다.</p>

    <h2>4. 데이터 보관 및 보안</h2>
    <p>Google Calendar API를 통해 접근하는 데이터는 Google의 보안 정책에 따라 보호됩니다.</p>
    <p>로컬 저장소에 저장되는 데이터는 사용자 기기에만 존재하며, 해당 기기의 보안 설정에 따릅니다.</p>
    <p>본 확장 프로그램은 데이터 보안을 위해 합리적인 조치를 취하고 있습니다.</p>

    <h2>5. 사용자 권리</h2>
    <p>사용자는 언제든지 Google 계정 설정(myaccount.google.com)에서 본 확장 프로그램에 부여된 Google 캘린더 접근 권한을 철회할 수 있습니다.</p>
    <p>확장 프로그램을 제거함으로써 로컬에 저장된 모든 데이터는 자동으로 삭제됩니다.</p>
    <p>문의사항이 있으시면 언제든지 <a href="mailto:utj440077@gmail.com">utj440077@gmail.com</a>로 연락 주시기 바랍니다.</p>

    <h2>6. 개인정보처리방침 변경</h2>
    <p>본 개인정보처리방침은 법률 및 서비스 변경사항을 반영하기 위해 업데이트될 수 있습니다. 변경사항은 본 페이지를 통해 공지하며, 중요한 변경사항의 경우 확장 프로그램 업데이트를 통해 사용자에게 알릴 수 있습니다.</p>

    <h2>7. 문의</h2>
    <p>본 개인정보처리방침에 대한 질문이나 우려사항이 있으시면 <a href="utj440077@gmail.com">utj440077@gmail.com</a>로 연락 주시기 바랍니다.</p>

    <div class="footer">
        <p>&copy; 2025 utj99. All rights reserved.</p>
        <a href="https://utj99.github.io/Lunar2GoogleCalender/">홈페이지</a> | <a href="">서비스 약관</a>
    </div>
</body>
</html>
