---
layout: page
title: Schedule
permalink: /schedule/
---

The Expo takes place on **Tuesday, November 3, 2026**. All times below are in **Eastern Standard Time (EST, UTC−5)**, using the 24-hour clock.

Each technical talk has a 15-minute slot: approximately 12 minutes for the presentation and 3 minutes for questions and transition.

<style>
  .expo-schedule {
    table-layout: fixed;
  }
  .expo-schedule th,
  .expo-schedule td {
    overflow-wrap: anywhere;
    vertical-align: top;
  }
  .expo-schedule th:nth-child(1) { width: 15%; }
  .expo-schedule th:nth-child(2) { width: 48%; }
  .expo-schedule th:nth-child(3) { width: 23%; }
  .expo-schedule th:nth-child(4) { width: 14%; }
  .expo-schedule .session-heading th {
    width: auto;
    background: #eee;
    text-align: left;
  }
  @media (max-width: 48em) {
    .expo-schedule,
    .expo-schedule tbody,
    .expo-schedule tr,
    .expo-schedule td,
    .expo-schedule .session-heading th {
      display: block;
      width: 100%;
    }
    .expo-schedule thead {
      position: absolute;
      width: 1px;
      height: 1px;
      padding: 0;
      margin: -1px;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      white-space: nowrap;
      border: 0;
    }
    .expo-schedule tr:not(.session-heading) {
      border-top: 1px solid #e5e5e5;
      padding: .4rem 0;
    }
    .expo-schedule td {
      display: flex;
      gap: .75rem;
      border: 0;
      padding: .2rem .5rem;
    }
    .expo-schedule td::before {
      content: attr(data-label);
      flex: 0 0 4rem;
      font-weight: bold;
    }
    .expo-schedule td span {
      min-width: 0;
    }
    .expo-schedule td.empty {
      display: none;
    }
  }
</style>

<table class="expo-schedule">
  <thead>
    <tr><th scope="col">When (UTC−5)</th><th scope="col">What</th><th scope="col">Who</th><th scope="col">Resources</th></tr>
  </thead>
  <tbody>
    <tr><td data-label="When"><span>15:30</span></td><td data-label="What"><span>Welcome and 2026 Competition Recap</span></td><td data-label="Who" class="empty"><span>—</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
  </tbody>
  <tbody>
    <tr class="session-heading"><th colspan="4" scope="rowgroup">Session 1</th></tr>
    <tr><td data-label="When"><span>15:40</span></td><td data-label="What"><span><a href="{{ '/invited_speaker/' | relative_url }}#kinodynamic-motion-coordination-for-multi-robot-teams">Kinodynamic Motion Coordination for Multi-Robot Teams</a> (Invited Talk 1)</span></td><td data-label="Who"><span>Wolfgang Hönig</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
    <tr><td data-label="When"><span>16:25</span></td><td data-label="What"><span>Break</span></td><td data-label="Who" class="empty"><span>—</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
  </tbody>
  <tbody>
    <tr class="session-heading"><th colspan="4" scope="rowgroup">Session 2</th></tr>
    <tr><td data-label="When"><span>16:35</span></td><td data-label="What"><span>[Team ターボババア] Predict What Will Actually Happen: A Tick-Mirrored Executor for Lifelong MAPF under Stochastic Delays</span></td><td data-label="Who"><span>Minjun Kim</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
    <tr><td data-label="When"><span>16:50</span></td><td data-label="What"><span>[Team Ash] Large-Scale Multi-Agent Path Finding with Directional Guidance and Variable-Duration Actions</span></td><td data-label="Who"><span>Alejandro Suárez-Hernández</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
    <tr><td data-label="When"><span>17:05</span></td><td data-label="What"><span>[Team Mygo] From Following to Map- and Delay-Aware Platooning</span></td><td data-label="Who"><span>Meiqi Tu</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
    <tr><td data-label="When"><span>17:20</span></td><td data-label="What"><span>[Team Trzy Kwaterki] Restricting Agents, Guiding Paths, Forming Convoys and Other Mechanisms for Lifelong Multi-Agent Pickup and Delivery in the League of Robot Runners 2026</span></td><td data-label="Who"><span>Jan Wangrat</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
    <tr><td data-label="When"><span>17:35</span></td><td data-label="What"><span>Break</span></td><td data-label="Who" class="empty"><span>—</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
  </tbody>
  <tbody>
    <tr class="session-heading"><th colspan="4" scope="rowgroup">Session 3</th></tr>
    <tr><td data-label="When"><span>17:45</span></td><td data-label="What"><span><a href="{{ '/invited_speaker/' | relative_url }}#deepfleet-multi-agent-foundation-models-for-mobile-robots">DeepFleet: Multi-Agent Foundation Models for Mobile Robots</a> (Invited Talk 2)</span></td><td data-label="Who"><span>Ameya Agaskar</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
  </tbody>
  <tbody>
    <tr class="session-heading"><th colspan="4" scope="rowgroup">Session 4</th></tr>
    <tr><td data-label="When"><span>18:30</span></td><td data-label="What"><span>Award Ceremony and Community Meeting</span></td><td data-label="Who" class="empty"><span>—</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
    <tr><td data-label="When"><span>18:55</span></td><td data-label="What"><span>Closing</span></td><td data-label="Who" class="empty"><span>—</span></td><td data-label="Resources" class="empty"><span>—</span></td></tr>
  </tbody>
</table>
