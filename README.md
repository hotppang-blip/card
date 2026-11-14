[index.html](https://github.com/user-attachments/files/34853601/index.html)
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>윤미선 팀장 | 인카금융서비스 제이어스 총괄 엔슈런스본부</title>
  <meta name="description" content="당신의 삶에 든든한 기준을 세우는 금융·보험 파트너, 인카금융서비스 윤미선 팀장입니다." />
  
  <!-- Open Graph (카카오톡 / SNS 공유 썸네일 카드 최적화) -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://hotppang-blip.github.io/card/" />
  <meta property="og:title" content="윤미선 팀장 | 인카금융서비스 엔슈런스본부" />
  <meta property="og:description" content="1:1 맞춤 보장 분석 및 재무 설계 상담 · 연락처 저장 및 간편 상담 신청" />
  <meta property="og:image" content="https://hotppang-blip.github.io/card/profile.jpg" />

  <!-- Google Fonts: Pretendard & Noto Serif KR -->
  <link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.min.css" />
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@600;700&display=swap" rel="stylesheet">
  
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />
  
  <!-- QRCode.js -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>

  <style>
    :root {
      --bg-outer: #0b0d10;
      --bg-card: #14171c;
      --bg-surface: #1d222a;
      --bg-surface-hover: #262c36;
      --navy-deep: #0f172a;
      --gold-primary: #d4af37;
      --gold-light: #f3e5ab;
      --gold-dark: #aa821c;
      --text-main: #f8fafc;
      --text-sub: #94a3b8;
      --text-muted: #64748b;
      --border-subtle: rgba(255, 255, 255, 0.08);
      --border-gold: rgba(212, 175, 55, 0.35);
      --shadow-card: 0 24px 60px rgba(0, 0, 0, 0.75);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      -webkit-tap-highlight-color: transparent;
    }

    body {
      font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
      background-color: var(--bg-outer);
      color: var(--text-main);
      display: flex;
      justify-content: center;
      align-items: flex-start;
      min-height: 100vh;
      line-height: 1.5;
    }

    .card-container {
      width: 100%;
      max-width: 430px;
      min-height: 100vh;
      background: linear-gradient(180deg, #181c23 0%, var(--bg-card) 45%, #101318 100%);
      position: relative;
      overflow-x: hidden;
      box-shadow: var(--shadow-card);
      padding-bottom: 44px;
    }

    /* Top Header & Subtle Gold Accent */
    .top-banner {
      height: 148px;
      background: radial-gradient(circle at 80% 20%, rgba(212, 175, 55, 0.16), transparent 60%),
                  linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
      position: relative;
      border-bottom: 1px solid var(--border-gold);
      padding: 20px 22px;
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
    }

    .company-badge {
      display: inline-flex;
      flex-direction: column;
      gap: 2px;
    }

    .company-name {
      font-size: 13px;
      font-weight: 700;
      letter-spacing: 0.06em;
      color: var(--gold-primary);
      text-transform: uppercase;
    }

    .branch-name {
      font-size: 11.5px;
      color: var(--text-sub);
      font-weight: 500;
    }

    .top-actions {
      display: flex;
      gap: 8px;
    }

    .icon-btn {
      width: 36px;
      height: 36px;
      border-radius: 50%;
      background: rgba(15, 23, 42, 0.7);
      border: 1px solid var(--border-subtle);
      color: var(--text-main);
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: all 0.2s ease;
      backdrop-filter: blur(8px);
    }

    .icon-btn:hover {
      border-color: var(--gold-primary);
      color: var(--gold-primary);
      transform: translateY(-1px);
    }

    /* Profile Section */
    .profile-section {
      padding: 0 24px;
      margin-top: -64px;
      position: relative;
      z-index: 2;
      text-align: center;
    }

    .avatar-wrapper {
      width: 124px;
      height: 124px;
      margin: 0 auto 16px;
      position: relative;
      border-radius: 50%;
      padding: 4px;
      background: linear-gradient(135deg, var(--gold-primary), #475569, var(--gold-dark));
      box-shadow: 0 12px 28px rgba(0, 0, 0, 0.55);
    }

    .avatar-inner {
      width: 100%;
      height: 100%;
      border-radius: 50%;
      overflow: hidden;
      background-color: #1e293b;
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
    }

    .avatar-inner img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: center top;
    }

    .avatar-fallback {
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background: linear-gradient(145deg, #27303f, #161b24);
      color: var(--gold-light);
    }

    .avatar-fallback span {
      font-family: 'Noto Serif KR', serif;
      font-size: 32px;
      font-weight: 700;
      letter-spacing: 2px;
    }

    .name-row {
      display: flex;
      align-items: baseline;
      justify-content: center;
      gap: 8px;
      margin-bottom: 4px;
    }

    .user-name {
      font-size: 26px;
      font-weight: 800;
      letter-spacing: -0.02em;
      color: #ffffff;
    }

    .user-title {
      font-size: 15px;
      font-weight: 600;
      color: var(--gold-primary);
    }

    .user-org-detail {
      font-size: 13px;
      color: var(--text-sub);
      margin-bottom: 14px;
    }

    .slogan-box {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid var(--border-subtle);
      border-radius: 12px;
      padding: 12px 16px;
      font-size: 13.5px;
      color: #e2e8f0;
      line-height: 1.55;
      margin-bottom: 22px;
    }

    .slogan-box i {
      color: var(--gold-primary);
      font-size: 11px;
      margin: 0 4px;
      opacity: 0.85;
    }

    /* Quick Action Grid */
    .quick-actions {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 10px;
      padding: 0 22px;
      margin-bottom: 20px;
    }

    .action-item {
      background: var(--bg-surface);
      border: 1px solid var(--border-subtle);
      border-radius: 14px;
      padding: 13px 6px;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 7px;
      text-decoration: none;
      color: var(--text-main);
      transition: all 0.2s ease;
      cursor: pointer;
    }

    .action-item:hover, .action-item:active {
      background: var(--bg-surface-hover);
      border-color: var(--border-gold);
      transform: translateY(-2px);
    }

    .action-icon {
      width: 36px;
      height: 36px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 16px;
    }

    .icon-call { background: rgba(56, 189, 248, 0.14); color: #38bdf8; }
    .icon-sms { background: rgba(52, 211, 153, 0.14); color: #34d399; }
    .icon-form { background: rgba(168, 85, 247, 0.16); color: #c084fc; }
    .icon-mail { background: rgba(212, 175, 55, 0.16); color: var(--gold-primary); }

    .action-label {
      font-size: 12px;
      font-weight: 600;
      color: #e2e8f0;
    }

    /* Primary CTA Buttons */
    .cta-group {
      padding: 0 22px;
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-bottom: 26px;
    }

    .btn-primary-gold {
      width: 100%;
      padding: 15px 18px;
      border-radius: 14px;
      border: none;
      background: linear-gradient(135deg, #e5c158 0%, #c59b27 100%);
      color: #0f172a;
      font-size: 15px;
      font-weight: 800;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 9px;
      cursor: pointer;
      box-shadow: 0 8px 20px rgba(212, 175, 55, 0.25);
      transition: transform 0.15s ease, filter 0.15s ease;
    }

    .btn-primary-gold:active {
      transform: scale(0.985);
      filter: brightness(0.95);
    }

    .btn-secondary-form {
      width: 100%;
      padding: 14px 18px;
      border-radius: 14px;
      border: 1px solid var(--border-gold);
      background: rgba(212, 175, 55, 0.08);
      color: var(--gold-light);
      font-size: 14.5px;
      font-weight: 700;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 9px;
      text-decoration: none;
      cursor: pointer;
      transition: all 0.2s ease;
    }

    .btn-secondary-form:hover {
      background: rgba(212, 175, 55, 0.15);
    }

    /* Section Styling */
    .section-block {
      padding: 0 22px;
      margin-bottom: 24px;
    }

    .section-title {
      font-size: 13px;
      font-weight: 700;
      color: var(--gold-primary);
      letter-spacing: 0.04em;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 7px;
    }

    .section-title::after {
      content: '';
      flex: 1;
      height: 1px;
      background: var(--border-subtle);
    }

    /* Info List */
    .info-card {
      background: var(--bg-surface);
      border: 1px solid var(--border-subtle);
      border-radius: 16px;
      overflow: hidden;
    }

    .info-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 14px 16px;
      border-bottom: 1px solid var(--border-subtle);
      text-decoration: none;
      color: inherit;
      transition: background 0.15s ease;
    }

    .info-row:last-child {
      border-bottom: none;
    }

    .info-row:hover {
      background: rgba(255, 255, 255, 0.02);
    }

    .info-left {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .info-icon {
      width: 32px;
      height: 32px;
      border-radius: 8px;
      background: rgba(255, 255, 255, 0.05);
      color: var(--gold-primary);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 13px;
      flex-shrink: 0;
    }

    .info-meta {
      display: flex;
      flex-direction: column;
    }

    .info-label {
      font-size: 11px;
      color: var(--text-muted);
    }

    .info-value {
      font-size: 13.5px;
      font-weight: 600;
      color: var(--text-main);
      word-break: break-all;
    }

    .copy-mini-btn {
      background: rgba(255, 255, 255, 0.06);
      border: 1px solid var(--border-subtle);
      color: var(--text-sub);
      font-size: 11px;
      padding: 5px 9px;
      border-radius: 6px;
      cursor: pointer;
      flex-shrink: 0;
      margin-left: 8px;
    }

    .copy-mini-btn:hover {
      color: #fff;
      border-color: var(--gold-primary);
    }

    /* Specialty Tags */
    .specialty-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
    }

    .specialty-item {
      background: var(--bg-surface);
      border: 1px solid var(--border-subtle);
      border-radius: 14px;
      padding: 14px;
      display: flex;
      flex-direction: column;
      gap: 6px;
    }

    .specialty-item i {
      color: var(--gold-primary);
      font-size: 16px;
    }

    .specialty-title {
      font-size: 13.5px;
      font-weight: 700;
      color: #f1f5f9;
    }

    .specialty-desc {
      font-size: 11.5px;
      color: var(--text-sub);
      line-height: 1.4;
    }

    /* Career Highlight */
    .career-box {
      background: linear-gradient(145deg, rgba(30, 41, 59, 0.65), rgba(20, 23, 28, 0.9));
      border: 1px solid var(--border-subtle);
      border-radius: 16px;
      padding: 16px;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .career-item {
      display: flex;
      align-items: flex-start;
      gap: 10px;
      font-size: 13px;
      color: #cbd5e1;
    }

    .career-dot {
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: var(--gold-primary);
      margin-top: 7px;
      flex-shrink: 0;
    }

    /* Footer */
    .card-footer {
      text-align: center;
      padding: 16px 22px 0;
      font-size: 11.5px;
      color: var(--text-muted);
    }

    /* Modal (QR & Share) */
    .modal-overlay {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.78);
      backdrop-filter: blur(6px);
      display: none;
      align-items: center;
      justify-content: center;
      z-index: 100;
      padding: 20px;
    }

    .modal-overlay.active {
      display: flex;
    }

    .modal-card {
      background: #1a1f27;
      border: 1px solid var(--border-gold);
      border-radius: 22px;
      width: 100%;
      max-width: 340px;
      padding: 26px 22px;
      text-align: center;
      position: relative;
      box-shadow: 0 25px 50px rgba(0, 0, 0, 0.85);
    }

    .modal-close {
      position: absolute;
      top: 16px;
      right: 16px;
      background: none;
      border: none;
      color: var(--text-sub);
      font-size: 18px;
      cursor: pointer;
    }

    .modal-title {
      font-size: 17px;
      font-weight: 700;
      color: #fff;
      margin-bottom: 6px;
    }

    .modal-sub {
      font-size: 12.5px;
      color: var(--text-sub);
      margin-bottom: 18px;
    }

    #qrcode-box {
      background: #ffffff;
      padding: 14px;
      border-radius: 14px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 16px;
    }

    .url-pill {
      background: rgba(0, 0, 0, 0.35);
      border: 1px solid var(--border-subtle);
      border-radius: 10px;
      padding: 9px 12px;
      font-size: 12px;
      color: var(--gold-light);
      margin-bottom: 14px;
      word-break: break-all;
    }

    /* Toast Notification */
    .toast {
      position: fixed;
      bottom: 28px;
      left: 50%;
      transform: translateX(-50%) translateY(20px);
      background: rgba(15, 23, 42, 0.96);
      border: 1px solid var(--gold-primary);
      color: #fff;
      padding: 11px 20px;
      border-radius: 999px;
      font-size: 13px;
      font-weight: 600;
      opacity: 0;
      pointer-events: none;
      transition: all 0.25s ease;
      z-index: 200;
      white-space: nowrap;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.6);
    }

    .toast.show {
      opacity: 1;
      transform: translateX(-50%) translateY(0);
    }
  </style>
</head>
<body>

  <main class="card-container">
    <!-- Top Header -->
    <header class="top-banner">
      <div class="company-badge">
        <span class="company-name">INCAR FINANCIAL SERVICES</span>
        <span class="branch-name">제이어스 총괄 · 엔슈런스본부</span>
      </div>
      <div class="top-actions">
        <button class="icon-btn" onclick="openQrModal()" title="QR코드 보기" aria-label="QR코드">
          <i class="fa-solid fa-qrcode"></i>
        </button>
        <button class="icon-btn" onclick="shareCard()" title="명함 공유하기" aria-label="공유하기">
          <i class="fa-solid fa-arrow-up-from-bracket"></i>
        </button>
      </div>
    </header>

    <!-- Profile Identity -->
    <section class="profile-section">
      <div class="avatar-wrapper">
        <div class="avatar-inner">
          <!-- 깃허브 card 저장소에 profile.jpg 파일을 함께 올리시면 자동으로 사진이 표시됩니다 -->
          <img src="profile.jpg" alt="윤미선 팀장 프로필" onerror="this.style.display='none'; document.getElementById('avatarFallback').style.display='flex';" />
          <div id="avatarFallback" class="avatar-fallback" style="display: none;">
            <span>윤미선</span>
          </div>
        </div>
      </div>

      <div class="name-row">
        <h1 class="user-name">윤미선</h1>
        <span class="user-title">팀장</span>
      </div>
      <p class="user-org-detail">인카금융서비스(주) 제이어스 총괄 엔슈런스본부</p>

      <div class="slogan-box">
        <i class="fa-solid fa-quote-left"></i>
        고객의 인생 여정에 흔들림 없는 기준을 세우는<br>
        <strong>1:1 맞춤 보장 분석 · 금융 파트너</strong>입니다.
        <i class="fa-solid fa-quote-right"></i>
      </div>
    </section>

    <!-- 4 Quick Actions -->
    <section class="quick-actions">
      <a href="tel:010-4209-8927" class="action-item">
        <div class="action-icon icon-call"><i class="fa-solid fa-phone"></i></div>
        <span class="action-label">전화걸기</span>
      </a>
      <a href="sms:010-4209-8927" class="action-item">
        <div class="action-icon icon-sms"><i class="fa-solid fa-comment-sms"></i></div>
        <span class="action-label">문자문의</span>
      </a>
      <a href="https://forms.gle/WYDmE1G7Jpt35BSf6" target="_blank" rel="noopener noreferrer" class="action-item">
        <div class="action-icon icon-form"><i class="fa-solid fa-file-signature"></i></div>
        <span class="action-label">상담신청</span>
      </a>
      <a href="mailto:1010h1016@naver.com" class="action-item">
        <div class="action-icon icon-mail"><i class="fa-solid fa-envelope"></i></div>
        <span class="action-label">이메일</span>
      </a>
    </section>

    <!-- Main Call-To-Action Buttons -->
    <section class="cta-group">
      <button class="btn-primary-gold" onclick="downloadVCard()">
        <i class="fa-solid fa-address-book"></i>
        스마트폰 연락처 바로 저장
      </button>
      <a href="https://forms.gle/WYDmE1G7Jpt35BSf6" target="_blank" rel="noopener noreferrer" class="btn-secondary-form">
        <i class="fa-solid fa-clipboard-check"></i>
        1:1 무료 보장분석 · 상담 신청서 작성
      </a>
    </section>

    <!-- Contact Details -->
    <section class="section-block">
      <h2 class="section-title">CONTACT & LINKS</h2>
      <div class="info-card">
        <div class="info-row">
          <a href="tel:010-4209-8927" class="info-left">
            <div class="info-icon"><i class="fa-solid fa-mobile-screen-button"></i></div>
            <div class="info-meta">
              <span class="info-label">휴대폰 직통번호</span>
              <span class="info-value">010-4209-8927</span>
            </div>
          </a>
          <button class="copy-mini-btn" onclick="copyText('010-4209-8927', '전화번호가 복사되었습니다.')">복사</button>
        </div>

        <div class="info-row">
          <a href="mailto:1010h1016@naver.com" class="info-left">
            <div class="info-icon"><i class="fa-solid fa-envelope"></i></div>
            <div class="info-meta">
              <span class="info-label">이메일 문의</span>
              <span class="info-value">1010h1016@naver.com</span>
            </div>
          </a>
          <button class="copy-mini-btn" onclick="copyText('1010h1016@naver.com', '이메일 주소가 복사되었습니다.')">복사</button>
        </div>

        <div class="info-row">
          <a href="https://forms.gle/WYDmE1G7Jpt35BSf6" target="_blank" rel="noopener noreferrer" class="info-left">
            <div class="info-icon"><i class="fa-solid fa-list-check"></i></div>
            <div class="info-meta">
              <span class="info-label">간편 상담 신청 (Google Form)</span>
              <span class="info-value">forms.gle/WYDmE1G7Jpt35BSf6</span>
            </div>
          </a>
          <button class="copy-mini-btn" onclick="copyText('https://forms.gle/WYDmE1G7Jpt35BSf6', '상담 신청 링크가 복사되었습니다.')">복사</button>
        </div>

        <div class="info-row">
          <a href="https://instagram.com/nsu_misun" target="_blank" rel="noopener noreferrer" class="info-left">
            <div class="info-icon"><i class="fa-brands fa-instagram"></i></div>
            <div class="info-meta">
              <span class="info-label">인스타그램 채널</span>
              <span class="info-value">@nsu_misun</span>
            </div>
          </a>
          <button class="copy-mini-btn" onclick="copyText('https://instagram.com/nsu_misun', '인스타그램 주소가 복사되었습니다.')">복사</button>
        </div>
      </div>
    </section>

    <!-- Core Services -->
    <section class="section-block">
      <h2 class="section-title">EXPERTISE</h2>
      <div class="specialty-grid">
        <div class="specialty-item">
          <i class="fa-solid fa-shield-heart"></i>
          <div class="specialty-title">정밀 보장분석</div>
          <div class="specialty-desc">중복·과다 보험료 진단 및 핵심 담보 리모델링</div>
        </div>
        <div class="specialty-item">
          <i class="fa-solid fa-hand-holding-medical"></i>
          <div class="specialty-title">보험금 청구 대행</div>
          <div class="specialty-desc">놓치기 쉬운 숨은 보험금 확인 및 신속 청구 지원</div>
        </div>
        <div class="specialty-item">
          <i class="fa-solid fa-people-roof"></i>
          <div class="specialty-title">생애주기 맞춤설계</div>
          <div class="specialty-desc">태아·어린이부터 가족 건강·간병 플랜까지</div>
        </div>
        <div class="specialty-item">
          <i class="fa-solid fa-chart-line"></i>
          <div class="specialty-title">은퇴·연금 자산관리</div>
          <div class="specialty-desc">비과세 저축 및 안정적인 노후 현금흐름 구축</div>
        </div>
      </div>
    </section>

    <!-- Trust & Profile Summary -->
    <section class="section-block">
      <h2 class="section-title">PROFILE</h2>
      <div class="career-box">
        <div class="career-item">
          <span class="career-dot"></span>
          <span><strong>現) 인카금융서비스(주)</strong> 제이어스 총괄 엔슈런스본부 팀장</span>
        </div>
        <div class="career-item">
          <span class="career-dot"></span>
          <span>30여 개 생·손해보험사 상품 객관적 비교 분석 컨설팅</span>
        </div>
        <div class="career-item">
          <span class="career-dot"></span>
          <span>가입부터 보험금 청구 사후관리까지 전담 케어 시스템</span>
        </div>
      </div>
    </section>

    <footer class="card-footer">
      © 2026 윤미선 팀장 · 인카금융서비스 엔슈런스본부
    </footer>
  </main>

  <!-- QR Code Modal -->
  <div id="qrModal" class="modal-overlay" onclick="closeQrModal(event)">
    <div class="modal-card" onclick="event.stopPropagation()">
      <button class="modal-close" onclick="closeQrModal()"><i class="fa-solid fa-xmark"></i></button>
      <h3 class="modal-title">디지털 명함 QR코드</h3>
      <p class="modal-sub">상대방 카메라로 스캔하면 명함이 바로 열립니다.</p>
      <div id="qrcode-box"></div>
      <div class="url-pill">https://hotppang-blip.github.io/card/</div>
      <button class="btn-primary-gold" onclick="copyText('https://hotppang-blip.github.io/card/', '명함 링크가 복사되었습니다.')">
        <i class="fa-solid fa-link"></i> 명함 주소 복사하기
      </button>
    </div>
  </div>

  <!-- Toast -->
  <div id="toast" class="toast">복사되었습니다.</div>

  <script>
    const CARD_URL = 'https://hotppang-blip.github.io/card/';
    let qrGenerated = false;

    function showToast(msg) {
      const toast = document.getElementById('toast');
      toast.textContent = msg;
      toast.classList.add('show');
      setTimeout(() => {
        toast.classList.remove('show');
      }, 2200);
    }

    function copyText(text, message) {
      if (navigator.clipboard && window.isSecureContext) {
        navigator.clipboard.writeText(text).then(() => showToast(message));
      } else {
        const tempInput = document.createElement('input');
        tempInput.value = text;
        document.body.appendChild(tempInput);
        tempInput.select();
        document.execCommand('copy');
        document.body.removeChild(tempInput);
        showToast(message);
      }
    }

    function openQrModal() {
      const modal = document.getElementById('qrModal');
      modal.classList.add('active');
      if (!qrGenerated) {
        new QRCode(document.getElementById('qrcode-box'), {
          text: CARD_URL,
          width: 180,
          height: 180,
          colorDark: '#0f172a',
          colorLight: '#ffffff',
          correctLevel: QRCode.CorrectLevel.H
        });
        qrGenerated = true;
      }
    }

    function closeQrModal() {
      document.getElementById('qrModal').classList.remove('active');
    }

    function shareCard() {
      if (navigator.share) {
        navigator.share({
          title: '윤미선 팀장 | 인카금융서비스 엔슈런스본부',
          text: '인카금융서비스 윤미선 팀장의 모바일 디지털 명함입니다.',
          url: CARD_URL
        }).catch(() => {});
      } else {
        copyText(CARD_URL, '명함 링크가 클립보드에 복사되었습니다.');
      }
    }

    function downloadVCard() {
      const vcardLines = [
        'BEGIN:VCARD',
        'VERSION:3.0',
        'N:윤;미선;;;',
        'FN:윤미선 팀장 (인카금융서비스)',
        'ORG:인카금융서비스 제이어스 총괄 엔슈런스본부',
        'TITLE:팀장',
        'TEL;TYPE=CELL,VOICE:010-4209-8927',
        'EMAIL;TYPE=PREF,INTERNET:1010h1016@naver.com',
        'URL:' + CARD_URL,
        'NOTE:간편 상담 신청: https://forms.gle/WYDmE1G7Jpt35BSf6',
        'END:VCARD'
      ];
      const blob = new Blob([vcardLines.join('\r\n')], { type: 'text/vcard;charset=utf-8' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = '윤미선팀장_인카금융서비스.vcf';
      document.body.appendChild(a);
      a.click();
      document.body.removeChild(a);
      URL.revokeObjectURL(url);
      showToast('연락처(.vcf) 파일이 다운로드됩니다.');
    }
  </script>
</body>
</html>
