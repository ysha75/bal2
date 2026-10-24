
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>밸런스 게임 남녀 매칭 (현장 진행용)</title>
  <style>
    :root {
      --primary: #ff5a79;
      --primary-hover: #e04863;
      --bg: #f8f9fa;
      --card-bg: #ffffff;
      --text: #333333;
    }
    * { box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      margin: 0;
      padding: 16px;
      display: flex;
      justify-content: center;
    }
    .container {
      width: 100%;
      max-width: 500px;
      background: var(--card-bg);
      padding: 20px;
      border-radius: 16px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.08);
    }
    h1 {
      text-align: center;
      color: var(--primary);
      margin-top: 0;
      margin-bottom: 20px;
      font-size: 22px;
    }
    .step { display: none; }
    .step.active { display: block; }
    .input-group { margin-bottom: 8px; }
    label {
      display: block;
      font-weight: bold;
      margin-bottom: 6px;
      font-size: 14px;
    }
    input[type="text"], input[type="number"] {
      width: 100%;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 8px;
      font-size: 14px;
    }
    .setup-count-box {
      background: #fff5f7;
      padding: 12px 16px;
      border-radius: 12px;
      margin-bottom: 16px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .setup-count-box label { margin-bottom: 0; white-space: nowrap; }
    .btn-secondary {
      background-color: #6c757d;
      margin-top: 0;
      padding: 10px 14px;
      width: auto;
      white-space: nowrap;
    }
    .btn-secondary:hover { background-color: #5a6268; }
    .grid-2 {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }
    h3 { margin-top: 0; font-size: 18px; }
    h4 { margin: 10px 0 8px 0; font-size: 14px; }
    button {
      width: 100%;
      background-color: var(--primary);
      color: white;
      border: none;
      padding: 14px;
      border-radius: 10px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      margin-top: 16px;
      transition: background 0.2s;
    }
    button:hover { background-color: var(--primary-hover); }
    .q-card {
      background: #fff5f7;
      border-left: 4px solid var(--primary);
      padding: 14px;
      border-radius: 8px;
      margin-bottom: 16px;
    }
    .option-btn {
      background: white;
      color: var(--text);
      border: 2px solid #eee;
      margin-top: 6px;
      padding: 10px;
      text-align: left;
      font-weight: normal;
      font-size: 14px;
    }
    .option-btn.selected {
      border-color: var(--primary);
      background-color: #ffe6eb;
      color: var(--primary);
      font-weight: bold;
    }
    .progress {
      font-size: 13px;
      color: #666;
      margin-bottom: 12px;
      font-weight: bold;
    }
    .result-item {
      background: #f1f3f5;
      padding: 16px;
      border-radius: 10px;
      margin-bottom: 16px;
    }
    .couple-name {
      font-size: 18px;
      font-weight: bold;
      color: var(--primary);
      margin-bottom: 4px;
    }
    .match-rate {
      font-size: 14px;
      color: #666;
      margin-bottom: 12px;
      font-weight: 500;
    }
    .answer-detail {
      background: #ffffff;
      border-radius: 8px;
      padding: 10px;
      margin-top: 8px;
      border: 1px solid #e9ecef;
    }
    .detail-q-title {
      font-size: 12px;
      font-weight: bold;
      color: #495057;
      margin-bottom: 6px;
    }
    .answer-grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 6px;
      font-size: 12px;
    }
    .ans-box {
      padding: 8px;
      border-radius: 6px;
      background: #f8f9fa;
      word-break: break-all;
    }
    .ans-box.match {
      background: #e6fcf5;
      color: #0ca678;
      font-weight: bold;
    }
    .ans-box.mismatch {
      background: #fff5f5;
      color: #e03131;
    }
    .all-ranking-box {
      background: #ffffff;
      border: 1px solid #dee2e6;
      border-radius: 10px;
      padding: 14px;
      margin-top: 20px;
    }
    .ranking-item {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 8px 0;
      border-bottom: 1px solid #f1f3f5;
      font-size: 14px;
    }
    .ranking-item:last-child { border-bottom: none; }
  </style>
</head>
<body>

<div class="container">
  <h1>💖 밸런스 게임 커플 매칭 💖</h1>

  <!-- STEP 1: 인원 및 참가자 설정 -->
  <div id="step-1" class="step active">
    <div class="setup-count-box">
      <label for="pair-count">성별당 인원수:</label>
      <input type="number" id="pair-count" value="4" min="1" max="20">
      <button type="button" class="btn-secondary" onclick="generateInputs()">인원 변경</button>
    </div>

    <div class="setup-count-box">
      <label for="total-questions">진행할 질문 개수:</label>
      <input type="number" id="total-questions" value="5" min="1" max="20">
    </div>

    <h3>참가자 이름을 입력하세요</h3>
    <div class="grid-2">
      <div>
        <h4 id="man-title">남성 참가자 (4명)</h4>
        <div id="men-inputs-container"></div>
      </div>
      <div>
        <h4 id="woman-title">여성 참가자 (4명)</h4>
        <div id="women-inputs-container"></div>
      </div>
    </div>
    <button onclick="startLiveGame()">게임 시작하기</button>
  </div>

  <!-- STEP 2: 현장 실시간 질문 및 답변 입력 -->
  <div id="step-2" class="step">
    <div class="progress" id="live-progress">질문 1 / 5 진행 중</div>
    
    <div class="input-group">
      <label id="q-number-label">Q1. 질문 내용 입력</label>
      <input type="text" id="live-q-title" placeholder="예: 주말 데이트 스타일은?">
    </div>
    <div class="grid-2">
      <div class="input-group">
        <label>선택지 ①</label>
        <input type="text" id="live-q-opt1" placeholder="예: 집콕 휴식">
      </div>
      <div class="input-group">
        <label>선택지 ②</label>
        <input type="text" id="live-q-opt2" placeholder="예: 야외 액티비티">
      </div>
    </div>

    <hr style="margin: 20px 0; border:0; border-top:1px solid #eee;">

    <div class="progress" id="user-progress">참가자 1 / 8 명</div>
    <h3 id="current-user-title" style="color: var(--primary);">OOO 님의 선택 입력</h3>
    
    <div class="q-card">
      <div style="display: flex; gap: 10px;">
        <button type="button" class="option-btn" id="ans-btn-1" onclick="selectLiveAnswer(1)" style="margin-top:0; text-align:center;">①번 선택</button>
        <button type="button" class="option-btn" id="ans-btn-2" onclick="selectLiveAnswer(2)" style="margin-top:0; text-align:center;">②번 선택</button>
      </div>
    </div>

    <button onclick="nextLiveStep()">다음으로 넘어가기</button>
  </div>

  <!-- STEP 3: 최종 결과 -->
  <div id="step-3" class="step">
    <h3>🎉 최종 매칭 결과 🎉</h3>
    <div id="result-container"></div>
    
    <div class="all-ranking-box">
      <h4 style="margin-top:0; color:#495057;">📊 모든 참가자 전체 매칭 순위</h4>
      <div id="all-ranking-container"></div>
    </div>

    <button onclick="location.reload()" style="background:#6c757d; margin-top:20px;">처음부터 다시하기</button>
  </div>
</div>

<script>
  let men = [];
  let women = [];
  let participants = [];
  let totalQuestionsCount = 5;
  
  let currentQIdx = 0; // 현재 질문 번호 (0부터 시작)
  let currentUserIdx = 0; // 현재 참가자 번호 (0부터 시작)
  
  let questionsData = []; // 입력된 질문들과 선택지 저장
  let userAnswers = {}; // { "참가자이름": [1, 2, 1, 2, 1] }
  let currentTempAns = null; // 현재 참가자가 고른 임시 답변 (1 또는 2)

  window.addEventListener('DOMContentLoaded', () => {
    generateInputs();
  });

  function generateInputs() {
    const countInput = document.getElementById('pair-count');
    const count = parseInt(countInput.value, 10);

    if (isNaN(count) || count < 1) {
      alert("인원수는 1명 이상이어야 합니다.");
      countInput.value = 1;
      return;
    }

    document.getElementById('man-title').innerText = `남성 참가자 (${count}명)`;
    document.getElementById('woman-title').innerText = `여성 참가자 (${count}명)`;

    const menContainer = document.getElementById('men-inputs-container');
    const womenContainer = document.getElementById('women-inputs-container');

    menContainer.innerHTML = '';
    womenContainer.innerHTML = '';

    for (let i = 1; i <= count; i++) {
      const manGroup = document.createElement('div');
      manGroup.className = 'input-group';
      manGroup.innerHTML = `<input type="text" class="man-name" value="남자${i}">`;
      menContainer.appendChild(manGroup);

      const womanGroup = document.createElement('div');
      womanGroup.className = 'input-group';
      womanGroup.innerHTML = `<input type="text" class="woman-name" value="여자${i}">`;
      womenContainer.appendChild(womanGroup);
    }
  }

  function startLiveGame() {
    const qCountInput = document.getElementById('total-questions');
    totalQuestionsCount = parseInt(qCountInput.value, 10);

    if (isNaN(totalQuestionsCount) || totalQuestionsCount < 1) {
      alert("질문 개수는 1개 이상이어야 합니다.");
      return;
    }

    const manInputs = document.querySelectorAll('.man-name');
    const womanInputs = document.querySelectorAll('.woman-name');

    men = Array.from(manInputs).map((input, i) => input.value.trim() || `남자${i+1}`);
    women = Array.from(womanInputs).map((input, i) => input.value.trim() || `여자${i+1}`);

    participants = [...men, ...women];
    
    // 참가자별 답변 배열 초기화
    participants.forEach(p => {
      userAnswers[p] = [];
    });

    currentQIdx = 0;
    currentUserIdx = 0;
    questionsData = [];

    showStep(2);
    updateLiveScreen();
  }

  function updateLiveScreen() {
    document.getElementById('live-progress').innerText = `질문 ${currentQIdx + 1} / ${totalQuestionsCount} 진행 중`;
    document.getElementById('q-number-label').innerText = `Q${currentQIdx + 1}. 질문 내용 입력`;

    // 첫 번째 참가자 입력을 시작할 때만 질문/선택지 입력란 초기화 (같은 질문에 대해선 모든 참가자가 답해야 하므로)
    if (currentUserIdx === 0) {
      document.getElementById('live-q-title').value = '';
      document.getElementById('live-q-opt1').value = '';
      document.getElementById('live-q-opt2').value = '';
      document.getElementById('live-q-title').disabled = false;
      document.getElementById('live-q-opt1').disabled = false;
      document.getElementById('live-q-opt2').disabled = false;
    } else {
      // 이미 입력된 질문은 수정 못하게 잠금
      document.getElementById('live-q-title').disabled = true;
      document.getElementById('live-q-opt1').disabled = true;
      document.getElementById('live-q-opt2').disabled = true;
    }

    const userName = participants[currentUserIdx];
    document.getElementById('user-progress').innerText = `참가자 ${currentUserIdx + 1} / ${participants.length}명`;
    document.getElementById('current-user-title').innerText = `👉 [${userName}] 님의 선택 입력`;

    currentTempAns = null;
    document.getElementById('ans-btn-1').classList.remove('selected');
    document.getElementById('ans-btn-2').classList.remove('selected');
  }

  function selectLiveAnswer(optNum) {
    currentTempAns = optNum;
    const btn1 = document.getElementById('ans-btn-1');
    const btn2 = document.getElementById('ans-btn-2');

    if (optNum === 1) {
      btn1.classList.add('selected');
      btn2.classList.remove('selected');
    } else {
      btn2.classList.add('selected');
      btn1.classList.remove('selected');
    }
  }

  function nextLiveStep() {
    // 첫 번째 참가자 차례일 때는 질문과 선택지가 모두 채워져 있는지 확인
    if (currentUserIdx === 0) {
      const qTitle = document.getElementById('live-q-title').value.trim();
      const opt1 = document.getElementById('live-q-opt1').value.trim();
      const opt2 = document.getElementById('live-q-opt2').value.trim();

      if (!qTitle || !opt1 || !opt2) {
        alert("질문 내용과 선택지 1, 2번을 모두 입력해주세요!");
        return;
      }

      // 이번 질문 정보 저장
      questionsData.push({ title: qTitle, opt1: opt1, opt2: opt2 });
    }

    if (currentTempAns === null) {
      alert("참가자의 선택(① 또는 ②)을 체크해 주세요!");
      return;
    }

    // 현재 참가자의 현재 질문 답변 저장
    const userName = participants[currentUserIdx];
    userAnswers[userName].push(currentTempAns);

    // 다음 단계로 이동
    currentUserIdx++;

    if (currentUserIdx < participants.length) {
      // 다음 참가자 답변 입력으로 이동
      updateLiveScreen();
    } else {
      // 모든 참가자가 현재 질문에 답했음 -> 다음 질문으로 넘어가거나 결과로 감
      currentUserIdx = 0;
      currentQIdx++;

      if (currentQIdx < totalQuestionsCount) {
        updateLiveScreen();
      } else {
        calculateAndShowResults();
      }
    }
    window.scrollTo(0, 0);
  }

  function calculateAndShowResults() {
    let scores = [];

    men.forEach(m => {
      women.forEach(w => {
        let matchCount = 0;
        for (let i = 0; i < totalQuestionsCount; i++) {
          if (userAnswers[m][i] === userAnswers[w][i]) {
            matchCount++;
          }
        }
        const percent = Math.round((matchCount / totalQuestionsCount) * 100);
        scores.push({ man: m, woman: w, score: matchCount, percent });
      });
    });

    // 점수 높은 순으로 정렬
    scores.sort((a, b) => b.score - a.score);

    // 1:1 최적 매칭 알고리즘 (중복 매칭 방지)
    let matchedMen = new Set();
    let matchedWomen = new Set();
    let finalMatches = [];

    scores.forEach(item => {
      if (!matchedMen.has(item.man) && !matchedWomen.has(item.woman)) {
        matchedMen.add(item.man);
        matchedWomen.add(item.woman);
        finalMatches.push(item);
      }
    });

    // 최종 결과 화면 구성
    const resContainer = document.getElementById('result-container');
    resContainer.innerHTML = '';

    finalMatches.forEach((match, idx) => {
      const card = document.createElement('div');
      card.className = 'result-item';

      let detailsHtml = '';
      questionsData.forEach((q, qIdx) => {
        const manAnsNum = userAnswers[match.man][qIdx];
        const womanAnsNum = userAnswers[match.woman][qIdx];

        const manAnsText = manAnsNum === 1 ? q.opt1 : q.opt2;
        const womanAnsText = womanAnsNum === 1 ? q.opt1 : q.opt2;

        const isMatch = manAnsNum === womanAnsNum;
        const statusClass = isMatch ? 'match' : 'mismatch';

        detailsHtml += `
          <div class="answer-detail">
            <div class="detail-q-title">Q${qIdx + 1}. ${q.title}</div>
            <div class="answer-grid">
              <div class="ans-box ${statusClass}">
                👨 ${match.man}: ${manAnsText}
              </div>
              <div class="ans-box ${statusClass}">
                👩 ${match.woman}: ${womanAnsText}
              </div>
            </div>
          </div>
        `;
      });

      card.innerHTML = `
        <div class="couple-name">커플 ${idx + 1}: ${match.man} ❤️ ${match.woman}</div>
        <div class="match-rate">질문 일치: ${match.score} / ${totalQuestionsCount}개 (${match.percent}% 일치)</div>
        ${detailsHtml}
      `;

      resContainer.appendChild(card);
    });

    // 전체 순위 리스트 구성
    const rankingContainer = document.getElementById('all-ranking-container');
    rankingContainer.innerHTML = '';

    scores.forEach((item, idx) => {
      const rankRow = document.createElement('div');
      rankRow.className = 'ranking-item';
      rankRow.innerHTML = `
        <span><b>${idx + 1}위</b> ${item.man} & ${item.woman}</span>
        <span style="color: var(--primary); font-weight: bold;">${item.percent}% (${item.score}/${totalQuestionsCount})</span>
      `;
      rankingContainer.appendChild(rankRow);
    });

    showStep(3);
    window.scrollTo(0, 0);
  }

  function showStep(stepNum) {
    document.querySelectorAll('.step').forEach(el => el.classList.remove('active'));
    document.getElementById(`step-${stepNum}`).classList.add('active');
  }
</script>

</body>
</html>

