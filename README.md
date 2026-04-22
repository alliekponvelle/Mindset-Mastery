<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Module 42: Mindset Mastery | The Creator Plug Academy</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      background:
        radial-gradient(circle at top right, rgba(168,85,247,0.16), transparent 28%),
        linear-gradient(135deg, #06030d 0%, #0c0518 55%, #040210 100%);
      color: #101417;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.7;
    }
    a { color: #7c3aed; }
    .page { max-width: 1140px; margin: 0 auto; padding: 28px; }
    .hero {
      background:
        radial-gradient(circle at 86% 18%, rgba(244,114,182,0.22), transparent 24%),
        linear-gradient(135deg, #0b0416 0%, #140822 52%, #090311 100%);
      border: 1px solid rgba(255,255,255,0.08);
      border-radius: 8px;
      color: white;
      display: grid;
      gap: 28px;
      grid-template-columns: 1.08fr 0.92fr;
      padding: 44px;
    }
    .badge {
      background: linear-gradient(90deg, #a855f7, #7c3aed);
      border-radius: 8px;
      display: inline-block;
      font-size: 12px;
      font-weight: 900;
      letter-spacing: 1px;
      margin-bottom: 18px;
      padding: 8px 12px;
      text-transform: uppercase;
    }
    h1 {
      font-size: clamp(42px, 7vw, 78px);
      line-height: 0.95;
      letter-spacing: -2px;
      margin-bottom: 18px;
    }
    .subtitle { color: rgba(255,255,255,0.84); font-size: 21px; max-width: 680px; }
    .nav { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 24px; }
    .nav a {
      background: rgba(255,255,255,0.09);
      border: 1px solid rgba(255,255,255,0.16);
      border-radius: 8px;
      color: white;
      font-weight: 800;
      padding: 10px 14px;
      text-decoration: none;
    }
    .stats { display: grid; gap: 12px; grid-template-columns: repeat(3, 1fr); margin-top: 26px; }
    .stat {
      background: rgba(255,255,255,0.08);
      border: 1px solid rgba(255,255,255,0.14);
      border-radius: 8px;
      padding: 16px;
    }
    .stat strong {
      color: #fbbf24;
      display: block;
      font-size: 13px;
      letter-spacing: 1px;
      margin-bottom: 6px;
      text-transform: uppercase;
    }
    .mind-panel {
      background: rgba(0,0,0,0.3);
      border: 1px solid rgba(255,255,255,0.12);
      border-radius: 8px;
      padding: 22px;
    }
    .mind-screen {
      background: #080414;
      border: 1px solid rgba(168,85,247,0.26);
      border-radius: 8px;
      min-height: 310px;
      padding: 18px;
    }
    .signal {
      align-items: center;
      display: flex;
      gap: 10px;
      margin-bottom: 18px;
    }
    .signal-badge {
      background: #a855f7;
      border-radius: 8px;
      font-size: 12px;
      font-weight: 900;
      padding: 6px 9px;
    }
    .mind-card {
      background: rgba(255,255,255,0.07);
      border: 1px solid rgba(255,255,255,0.12);
      border-radius: 8px;
      margin-top: 12px;
      padding: 16px;
    }
    .mind-card b { color: white; display: block; font-size: 18px; }
    .mind-card span { color: rgba(255,255,255,0.68); display: block; margin-top: 4px; }
    .flow { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 18px; }
    .flow span {
      background: rgba(168,85,247,0.16);
      border: 1px solid rgba(168,85,247,0.32);
      border-radius: 8px;
      color: white;
      font-size: 12px;
      font-weight: 800;
      padding: 8px 10px;
    }
    .section {
      background: white;
      border: 1px solid rgba(16,20,23,0.1);
      border-radius: 8px;
      color: #101417;
      margin-top: 24px;
      padding: 30px;
    }
    .section h2 { color: #7c3aed; font-size: 34px; margin-bottom: 12px; }
    .section h3 { color: #2b0e49; font-size: 22px; margin: 24px 0 8px; }
    .lead { color: #34424a; font-size: 18px; max-width: 920px; }
    .grid { display: grid; gap: 16px; grid-template-columns: repeat(2, 1fr); margin-top: 18px; }
    .card {
      background: #fcfbff;
      border: 1px solid rgba(16,20,23,0.1);
      border-radius: 8px;
      color: #101417;
      padding: 20px;
    }
    .card h3 { margin-top: 0; }
    .card p,
    .card li,
    .section p,
    .section li,
    .section td,
    .section ol,
    .section ul {
      color: #101417;
    }
    .section strong { color: #111827; }
    ul, ol { margin: 10px 0 0 22px; }
    li { margin: 8px 0; }
    table {
      border: 1px solid rgba(16,20,23,0.14);
      border-collapse: collapse;
      margin-top: 14px;
      width: 100%;
    }
    th, td {
      border-bottom: 1px solid rgba(16,20,23,0.1);
      padding: 12px;
      text-align: left;
      vertical-align: top;
    }
    th {
      background: #140822;
      color: white;
      font-size: 13px;
      text-transform: uppercase;
    }
    .callout {
      background: #faf5ff;
      border-left: 5px solid #a855f7;
      border-radius: 8px;
      margin-top: 18px;
      padding: 16px 18px;
    }
    .warning {
      background: #fff7ed;
      border-left-color: #f59e0b;
    }
    .lesson {
      border-top: 1px solid rgba(16,20,23,0.1);
      margin-top: 24px;
      padding-top: 24px;
    }
    .lesson:first-of-type { border-top: 0; margin-top: 0; padding-top: 0; }
    .footer { color: rgba(255,255,255,0.72); font-size: 14px; margin-top: 24px; text-align: center; }
    @media (max-width: 880px) {
      .hero, .grid, .stats { grid-template-columns: 1fr; }
      .hero { padding: 28px; }
      table, thead, tbody, th, td, tr { display: block; }
      th { display: none; }
    }
  </style>
</head>
<body>
  <main class="page">
    <section class="hero">
      <div>
        <span class="badge">Module 42</span>
        <h1>Mindset Mastery</h1>
        <p class="subtitle">Your beliefs, identity, discipline, and resilience determine how far every strategy in this academy can actually take you.</p>
        <nav class="nav">
          <a href="#overview">Overview</a>
          <a href="#lessons">Lessons</a>
          <a href="#plan">30-Day Plan</a>
          <a href="#practices">Practices</a>
        </nav>
        <div class="stats">
          <div class="stat"><strong>Identity Shift</strong>Success starts when you stop waiting for permission and begin acting like the person you are becoming.</div>
          <div class="stat"><strong>Money Rewire</strong>Old stories about wealth shape your ceiling until you challenge and replace them.</div>
          <div class="stat"><strong>Daily Practice</strong>Mindset changes through repetition, not one motivational moment.</div>
        </div>
      </div>
      <div class="mind-panel">
        <div class="mind-screen">
          <div class="signal"><span class="signal-badge">RESET</span><strong>Operating system upgrade in progress</strong></div>
          <div class="mind-card"><b>Old Pattern</b><span>Fear, comparison, self-doubt, scattered effort.</span></div>
          <div class="mind-card"><b>New Pattern</b><span>Identity, discipline, focus, resilience, aligned action.</span></div>
          <div class="flow">
            <span>Belief</span><span>Behavior</span><span>Habit</span><span>Result</span><span>Identity</span>
          </div>
        </div>
      </div>
    </section>

    <section id="overview" class="section">
      <h2>Why Mindset Is the Real Business Strategy</h2>
      <p class="lead">Every module in this academy gives you tactics, systems, and plans. But mindset is the operating system underneath all of it. Your beliefs about money, success, failure, and yourself decide which actions you take, how long you persist, and whether you keep moving when the work gets hard.</p>
      <div class="grid">
        <div class="card">
          <h3>Why People Stall</h3>
          <p>Most people do not fail because they lack information. They fail because fear, doubt, resistance, and old identity patterns interrupt execution.</p>
        </div>
        <div class="card">
          <h3>What This Module Does</h3>
          <p>This module helps you rewire limiting beliefs, build discipline, handle fear, strengthen resilience, and align your behavior with the life and business you want.</p>
        </div>
      </div>
      <div class="callout">
        <strong>Core idea:</strong> the business is the easy part. You are the work.
      </div>
    </section>

    <section id="lessons" class="section">
      <h2>The 14-Lesson Playbook</h2>

      <article class="lesson">
        <h3>Lesson 1: Entrepreneurial Mindset vs. Employee Mindset</h3>
        <table>
          <thead><tr><th>Employee Mindset</th><th>Entrepreneur Mindset</th></tr></thead>
          <tbody>
            <tr><td>Wait for instructions</td><td>Create the plan and execute</td></tr>
            <tr><td>Avoid failure</td><td>Use failure as feedback</td></tr>
            <tr><td>Trade time for money</td><td>Build systems that create money</td></tr>
            <tr><td>Seek security</td><td>Seek freedom and opportunity</td></tr>
          </tbody>
        </table>
        <p>The shift to entrepreneurship is an identity reconstruction. You act your way into it. The goal is not to feel ready first, but to start behaving like a business owner now.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 2: Fixed vs. Growth Mindset</h3>
        <table>
          <thead><tr><th>Fixed Mindset</th><th>Growth Mindset</th></tr></thead>
          <tbody>
            <tr><td>"I failed at this."</td><td>"This attempt gave me information."</td></tr>
            <tr><td>"I'm not good at marketing."</td><td>"I have not mastered marketing yet."</td></tr>
            <tr><td>"They're just lucky."</td><td>"What can I learn from their strategy?"</td></tr>
            <tr><td>"I can't do this."</td><td>"I can't do this yet."</td></tr>
          </tbody>
        </table>
        <p>The word <strong>yet</strong> changes everything. It shifts failure from verdict to stage of development.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 3: Money Mindset</h3>
        <p>Your beliefs about money often formed in childhood and still influence your prices, actions, ceiling, and self-worth. Most limiting money beliefs are inherited stories, not facts.</p>
        <table>
          <thead><tr><th>Old Story</th><th>New Story</th></tr></thead>
          <tbody>
            <tr><td>Money is evil</td><td>Money is a tool</td></tr>
            <tr><td>Rich people are selfish</td><td>Wealth gives me more capacity to help</td></tr>
            <tr><td>I am bad with money</td><td>I am learning to manage money well</td></tr>
            <tr><td>I do not deserve this</td><td>I create value and value earns income</td></tr>
          </tbody>
        </table>
      </article>

      <article class="lesson">
        <h3>Lesson 4: Fear, Resistance, and the Work</h3>
        <div class="grid">
          <div class="card">
            <h3>What Resistance Looks Like</h3>
            <ul>
              <li>Researching forever instead of publishing</li>
              <li>Perfecting low-impact details</li>
              <li>Suddenly feeling too tired to do the important thing</li>
            </ul>
          </div>
          <div class="card">
            <h3>The Reframe</h3>
            <ul>
              <li>Fear of judgment</li>
              <li>Fear of failure</li>
              <li>Fear of success and change</li>
            </ul>
          </div>
        </div>
        <p>The more resistance you feel toward a meaningful task, the more likely it matters. Use resistance as a compass, not a stop sign.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 5: Self-Discipline and Consistency</h3>
        <ol>
          <li>Design your environment so good actions are easier.</li>
          <li>Use systems instead of waiting for motivation.</li>
          <li>Anchor habits to identity: "I am someone who shows up."</li>
          <li>Use the 2-minute rule to reduce friction and start.</li>
        </ol>
        <div class="callout warning">
          Burnout is usually not just hard work. It is hard work without meaning, rest, or visible progress.
        </div>
      </article>

      <article class="lesson">
        <h3>Lesson 6: Imposter Syndrome</h3>
        <p>You do not need to be the top expert to help someone. You only need to be honest, useful, and a few steps ahead of the person you are serving. Your real journey is enough qualification to create value.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 7: Comparison</h3>
        <p>Comparison becomes toxic when you measure your Chapter 3 against someone else's Chapter 30. Use comparison as research, not self-punishment. Study patterns, not status.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 8: Resilience</h3>
        <p>Failure is not the detour. It is part of the path. The useful question is never "Will I fail?" It is "What will I do next when something does not work?"</p>
        <ol>
          <li>What was the expected outcome?</li>
          <li>What actually happened?</li>
          <li>What explains the gap?</li>
          <li>What will I change next time?</li>
        </ol>
      </article>

      <article class="lesson">
        <h3>Lesson 9: Environment and Community</h3>
        <p>You become more like the people, conversations, and content around you. Audit your circle, protect your energy, and deliberately build creator community that stretches your standards upward.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 10: Productivity and Focus</h3>
        <table>
          <thead><tr><th>High-Value Work</th><th>Low-Value Busy Work</th></tr></thead>
          <tbody>
            <tr><td>Creating and publishing content</td><td>Endless logo and website tweaks</td></tr>
            <tr><td>Building and emailing your list</td><td>Tool hopping and research spirals</td></tr>
            <tr><td>Launching and selling</td><td>Looking productive instead of shipping</td></tr>
          </tbody>
        </table>
        <p>Protect deep work, time block, single-task, and plan tomorrow the night before.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 11: Emotional Intelligence</h3>
        <p>Self-awareness, self-regulation, empathy, and social skill all affect how you handle feedback, customers, collaborators, and stress. Business is human work. Emotional skill is a revenue skill.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 12: Vision, Goals, and Reverse Engineering</h3>
        <p>Start with vision, then translate it into 90-day sprints, then reduce that sprint into daily actions. Every large goal has a today's task hiding inside it.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 13: Spiritual and Holistic Foundations</h3>
        <p>Sustainable success needs anchoring. Values, purpose, rest, play, recovery, gratitude, and alignment matter because success without foundation often feels empty or collapses under pressure.</p>
      </article>

      <article class="lesson">
        <h3>Lesson 14: 30-Day Mindset Transformation Plan</h3>
        <div class="grid">
          <div class="card">
            <h3>Week 1: Awareness</h3>
            <ul>
              <li>Audit limiting beliefs about money and success</li>
              <li>Identify your top fear patterns</li>
              <li>Write your 3-year vision</li>
              <li>Start a wins journal</li>
            </ul>
          </div>
          <div class="card">
            <h3>Week 2: Rewire</h3>
            <ul>
              <li>Replace one core limiting belief</li>
              <li>Start daily gratitude</li>
              <li>Raise your income ceiling mentally</li>
              <li>Mute comparison triggers</li>
            </ul>
          </div>
          <div class="card">
            <h3>Week 3: Build Systems</h3>
            <ul>
              <li>Design your ideal workday</li>
              <li>Create a morning routine</li>
              <li>Identify top revenue activities</li>
              <li>Apply the 80/20 audit</li>
            </ul>
          </div>
          <div class="card">
            <h3>Week 4: Integrate</h3>
            <ul>
              <li>Reverse engineer your next 90 days</li>
              <li>Rewrite every old story with a growth version</li>
              <li>Make one environment upgrade</li>
              <li>Commit to one next-level resource</li>
            </ul>
          </div>
        </div>
      </article>
    </section>

    <section id="plan" class="section">
      <h2>Ongoing Mindset Practices</h2>
      <table>
        <thead><tr><th>Practice</th><th>Frequency</th><th>Purpose</th></tr></thead>
        <tbody>
          <tr><td>Gratitude journal</td><td>Daily</td><td>Rewires attention toward abundance</td></tr>
          <tr><td>Vision review</td><td>Daily</td><td>Keeps your North Star visible</td></tr>
          <tr><td>Wins journal</td><td>Daily</td><td>Pushes back on imposter syndrome</td></tr>
          <tr><td>Deep work block</td><td>Daily</td><td>Protects focus and output</td></tr>
          <tr><td>Weekly review</td><td>Weekly</td><td>Tracks progress and adjusts direction</td></tr>
          <tr><td>Community check-in</td><td>Weekly</td><td>Builds accountability and support</td></tr>
          <tr><td>Rest day</td><td>Weekly</td><td>Supports recovery and creativity</td></tr>
          <tr><td>90-day review</td><td>Quarterly</td><td>Reconnects goals to vision</td></tr>
        </tbody>
      </table>
    </section>

    <section id="practices" class="section">
      <h2>Final Shift</h2>
      <p class="lead">Your mindset is not fixed. It is a living system you are either shaping intentionally or allowing to shape you unconsciously. Every tool in the academy gets stronger when the person using it gets stronger too.</p>
      <div class="callout">
        <strong>Remember:</strong> this module gives you the hands to hold every other tool in the academy better.
      </div>
    </section>

    <p class="footer">Module 42 Complete - The Creator Plug Academy</p>
  </main>
</body>
</html>
