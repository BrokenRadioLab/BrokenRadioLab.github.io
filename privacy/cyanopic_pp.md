# Cyanopic — Privacy Policy

_Last updated: 4 August 2026_

Cyanopic ("the app") is a personal knowledge archive. You capture links, screenshots, and notes, and the app organizes them into your own archive. This policy explains what data the app handles and where it goes.

## Local-first storage

The items you save (links, text, images) and the knowledge derived from them are stored **on your device** in the app's local database. Capturing and browsing your archive work without sending your archive to us.

## AI organization (optional)

When AI organization is used, the **text of the content you saved** (for example a page title, description, or recognized text) is sent through a relay server operated by the developer to a third-party AI provider (**OpenAI**) to generate a summary, tags, and suggestions. Only the content needed for that analysis is sent. The app does not send your private notes for AI processing.

## AI image analysis (optional, off by default)

If you turn on **"AI image analysis (vision)"** in Settings, images attached to your saved items (for example screenshots or images captured from a post) are **uploaded** through the developer-operated relay server and forwarded to the third-party AI provider (**OpenAI**) so the AI can read them directly. The relay passes images through in memory only — it does **not store** them and does not write them to logs. Only the resulting analysis text is stored on your device. Per OpenAI's standard API policy, API inputs are not used for model training and may be retained for up to 30 days for abuse monitoring. This feature is off by default and images are never uploaded while it is off.

## Full Instagram capture (optional, off by default)

If you turn on **"Full Instagram capture"** in Settings and sign in to Instagram inside the app, your Instagram **session cookie** is sent to the relay server only to fetch the post you chose to save (full caption and photos). The cookie exists on the server only for the duration of that request and is deleted immediately afterwards; it is used solely for requests to Instagram itself and is never provided to any other third party. This feature is off by default.

## Device identifier

A device identifier (Android ID) is sent to the relay server for access control and server logs. It is not used for advertising and is not shared with third parties for advertising.

## Location / place features

When you use place or map features, place names and coordinates are sent to **Naver Maps / Naver Search APIs** to resolve and display locations. The app does not track your real-time location in the background.

## On-device processing

Text recognition from images (OCR) runs **on your device**; images are never uploaded for OCR. Images leave your device only when you enable the optional AI image analysis feature described above.

## What we do NOT do

- No advertising and no advertising identifiers.
- No third-party analytics SDKs.
- No account or login; we do not collect your name, email, or phone number.

## Data transmission security

During this closed beta, requests to the relay server are sent over plain HTTP and are **not encrypted in transit**. Do not save highly sensitive information during the beta. Encrypted transport (HTTPS) is planned before a public release.

## Data retention & deletion

You can delete any saved item within the app. Because your archive lives on your device, uninstalling the app removes its local data. Server-side logs contain only the device identifier and request metadata needed to operate the relay. To request deletion of server-side log entries, contact <brokenradiolab@gmail.com>.

## Children

Cyanopic is not directed to children under 13.

## Changes

We may update this policy; material changes will be reflected here with a new date.

## Contact

Questions: <brokenradiolab@gmail.com> (BrokenRadioLab).

---

# Cyanopic — 개인정보처리방침

_최종 수정: 2026년 8월 4일_

Cyanopic("본 앱")은 개인 지식 아카이브 앱입니다. 링크·스크린샷·메모를 저장하면 앱이 이를 나만의 아카이브로 정리합니다. 본 방침은 앱이 어떤 데이터를 다루고 어디로 전송하는지 설명합니다.

## 로컬 우선 저장

저장한 항목(링크·텍스트·이미지)과 그로부터 생성된 지식은 **기기 내부**의 앱 로컬 데이터베이스에 저장됩니다. 캡처와 아카이브 열람은 데이터를 외부로 보내지 않고 동작합니다.

## AI 정리 (선택 기능)

AI 정리를 사용할 경우, **저장한 콘텐츠의 텍스트**(예: 페이지 제목·설명·인식된 텍스트)가 개발자가 운영하는 중계 서버를 거쳐 제3자 AI 제공자(**OpenAI**)로 전송되어 요약·태그·추천을 생성합니다. 해당 분석에 필요한 콘텐츠만 전송되며, 사용자의 비공개 메모는 AI 처리를 위해 전송하지 않습니다.

## AI 이미지 분석 (선택 기능, 기본 꺼짐)

설정에서 **"AI 이미지 분석 (vision)"**을 켜면, 저장한 항목에 포함된 이미지(예: 스크린샷, 게시물에서 캡처된 이미지)가 개발자가 운영하는 중계 서버를 거쳐 제3자 AI 제공자(**OpenAI**)로 **업로드**되어 AI가 이미지를 직접 분석합니다. 중계 서버는 이미지를 메모리에서 전달만 하며 **저장하지 않고** 로그에도 기록하지 않습니다. 분석 결과 텍스트만 기기에 저장됩니다. OpenAI의 표준 API 정책상 입력 데이터는 모델 학습에 사용되지 않으며 남용 모니터링 목적으로 최대 30일 보관될 수 있습니다. 이 기능은 기본적으로 꺼져 있으며, 꺼진 동안에는 이미지가 절대 업로드되지 않습니다.

## Instagram 전체 캡처 (선택 기능, 기본 꺼짐)

설정에서 **"Instagram 전체 캡처"**를 켜고 앱 내에서 Instagram에 로그인하면, 사용자가 저장하기로 선택한 게시물(전체 캡션과 사진)을 가져오기 위해서만 사용자의 Instagram **세션 쿠키**가 중계 서버로 전송됩니다. 쿠키는 해당 요청을 처리하는 동안에만 서버에 존재하고 처리 직후 즉시 삭제되며, 오직 Instagram에 대한 요청에만 사용되고 그 외 어떤 제3자에게도 제공되지 않습니다. 이 기능은 기본적으로 꺼져 있습니다.

## 기기 식별자

중계 서버 접근 제어와 서버 로그를 위해 기기 식별자(Android ID)가 전송됩니다. 광고 목적으로 사용되지 않으며 광고 목적의 제3자 공유도 하지 않습니다.

## 위치 / 장소 기능

장소·지도 기능 사용 시 장소명과 좌표가 **네이버 지도/검색 API**로 전송되어 위치를 해석·표시합니다. 백그라운드에서 실시간 위치를 추적하지 않습니다.

## 기기 내 처리

이미지의 텍스트 인식(OCR)은 **기기 내부**에서 처리되며, OCR을 위해 이미지를 업로드하지 않습니다. 이미지는 위의 선택 기능인 AI 이미지 분석을 켠 경우에만 기기 밖으로 전송됩니다.

## 하지 않는 것

- 광고 및 광고 식별자 없음.
- 제3자 분석 SDK 없음.
- 계정·로그인 없음. 이름·이메일·전화번호를 수집하지 않음.

## 전송 구간 보안

본 비공개 베타 기간 동안 중계 서버 요청은 일반 HTTP로 전송되어 **전송 구간이 암호화되지 않습니다**. 베타 기간에는 민감한 정보를 저장하지 마세요. 정식 출시 전 암호화 전송(HTTPS)을 적용할 예정입니다.

## 보관 및 삭제

앱 내에서 저장한 항목을 삭제할 수 있습니다. 아카이브는 기기에 저장되므로 앱을 삭제하면 로컬 데이터가 제거됩니다. 서버 로그에는 중계 운영에 필요한 기기 식별자와 요청 메타데이터만 포함됩니다. 서버 로그 삭제를 요청하시려면 <brokenradiolab@gmail.com>으로 연락해 주세요.

## 아동

Cyanopic은 만 13세 미만 아동을 대상으로 하지 않습니다.

## 변경

본 방침은 변경될 수 있으며, 중요한 변경 시 새 날짜와 함께 이 페이지에 반영됩니다.

## 문의

문의: <brokenradiolab@gmail.com> (BrokenRadioLab).
