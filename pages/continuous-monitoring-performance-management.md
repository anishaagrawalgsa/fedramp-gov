---
layout: full-width
title: Continuous Monitoring Performance Management
permalink: /conmon-performance-mgmt/
body-class: wiki

---

<div class="wiki-main-wrapper">
<p>When a CSP receives a JAB P-ATO letter for its cloud system, that letter comes with the following minimum requirements: </p>
<ul>
<li>The CSP satisfies the requirement of implementing ConMon activities as documented in FedRAMP’s Continuous Monitoring Strategy Guide and the CSP’s ConMon Plan; </li>
<li>The CSP mitigates all open Plan of Action and Milestones (POA&M) action items, agreed to in the Security Assessment Report (SAR), within the appropriate timeframe as defined in the agreed POA&M; and</li>
<li>The CSP identifies and manages significant changes or critical vulnerabilities in accordance with applicable Federal law, guidelines, and policies. </li>
</ul>

<p>Further, by accepting the P-ATO requirements outlined in the P-ATO letter,  the CSP agrees to maintain operational visibility, change control, and incident response functions defined in the <a href="{{site.baseurl}}/conmon-strategy">FedRAMP Continuous Monitoring Strategy Guide</a>. In addition, the CSP is expected to continue to follow NIST SP 800-37, Revision 2, Risk Management Framework for Information Systems and Organizations: A System Life Cycle Approach for Security and Privacy, and related NIST Risk Management Framework (RMF) guidance, and to effectively deploy all applicable security controls, as well as act in good faith to maintain the appropriate risk posture.</p>

<p>Failure to adhere to the requirements of the P-ATO may result in escalation actions by FedRAMP, outlined in subsequent sections of this document, as well as additional actions as FedRAMP deems appropriate.</p>

<p>While much of this information specifically addresses FedRAMP P-ATOs maintained by the JAB, CSPs with Agency ATOs also must maintain compliance with FedRAMP ConMon requirements outlined in the ATO letter. As outlined in the Agency ATO Performance Management section below, FedRAMP recommends Agencies create similar guides and/or use this FedRAMP Continuous Monitoring Performance Management Guide when maintaining FedRAMP Agency ATOs.</p>

 

<p><strong>Contents </strong></p>
<ol> 
<li><a href="#jab-p-ato-performance-mgmt">JAB P-ATO Performance Management</a>
	<ul>
<li><a href="#jab-escalation-levels-and-process">1.1 JAB Escalation Levels and Process</a></li>
<li><a href="#risk-deficiency-triggers">1.2 JAB ConMon Requirements: Risk Management Deficiency Triggers</a></li>
<li><a href="customer-demand">1.3 JAB Customer Demand</a></li>
	</ul>
</li>
<li><a href="ato-performance-mgmt">Agency ATO Performance Management</a>
	<ul>
<li><a href="agency-escalation-levels-process">2.1 Agency Escalation Levels and Process</a></li>
<li><a href="agency-conmon-risk-mgmt-triggers">2.2 Agency ConMon Requirements: Risk Management Deficiency Triggers</a></li>
<li><a href="fedramp-for-agency-atos">2.3 FedRAMP Responsibilities for Agency ATOs</a></li>
	</ul>
</li>
</ol>


<div id="jab-p-ato-performance-mgmt"><h2>JAB P-ATO Performance Management </h2>
<hr></div>
<div id="jab-escalation-levels-and-process">
<h3>JAB Escalation Levels and Process </h3>
<p>As a condition of a JAB P-ATO, the CSP agrees to meet the requirements described in the FedRAMP Continuous Monitoring Strategy Guide at <a href="https://www.fedramp.gov/documents/"><strong>https://www.fedramp.gov/documents/</strong></a>. If the CSP fails to meet the requirements, FedRAMP initiates an escalation process, which may result in one of the following escalation levels:</p>
<ul>
<li><strong>Detailed Finding Review (DFR):</strong> A request from the FedRAMP Point of Contact (POC) for the CSP’s security POC to assess a deficiency, and report the cause and remedy to FedRAMP. If the CSP does not resolve a DFR within the agreed upon timeframe, FedRAMP may escalate to a Corrective Action Plan.</li>
<li><strong>Corrective Action Plan (CAP):</strong> A request from the FedRAMP Director for the CSP’s system owner to perform a root-cause analysis and provide a formal plan for remediation. If the CSP does not resolve a CAP within the agreed upon timeframe, FedRAMP may suspend or revoke the system’s P-ATO.</li>
<li><strong>Suspension:</strong> A decision by the JAB to temporarily suspend a system’s P-ATO until identified deficiencies are resolved. If the CSP does not resolve a Suspension within the agreed upon timeframe, or if the FedRAMP Director and JAB determine the CSP can no longer meet FedRAMP compliance requirements, FedRAMP may revoke the system’s P-ATO.</li>
<li><strong>Revocation:</strong> A decision by the JAB to permanently revoke a system’s P-ATO. If revoked, the only way the system can obtain a P-ATO is by re-entering the JAB Authorization process as if the system were seeking a P-ATO for the first time.</li>
</ul>

<p>When FedRAMP identifies a deficiency in the CSP’s ConMon capabilities, it initiates the process depicted in Figure 1. FedRAMP Escalation Process, below.</p>
</section>
<p class="caption"><strong>Figure 1. FedRAMP Escalation Process</strong></p>
<img src="{{site.baseurl}}/assets/img/escalation-process.png" title="Escalation Process" alt="Escalation Process">
<p>The escalation process occurs as follows:</p>
<ol>
<li><strong>FedRAMP identifies a deficiency with the CSP’s ConMon information.</strong></li>
<li><strong>FedRAMP reviews the deficiency and compares it to the CSP’s past ConMon performance.</strong> As a result of the review, FedRAMP decides on one of the following actions:
	<ul>
<li>FedRAMP typically decides on an escalation level consistent with the guidance described in Section 2.2, JAB ConMon Requirements: Risk Management Deficiency Triggers.</li>
<li>FedRAMP may elect to simply monitor the CSP more closely and take no further action. If so, no notice is sent, and the process stops here.</li>
<li>FedRAMP may increase a CSP’s existing escalation level. For example, a CSP on a CAP may face Suspension.</li>
<li>In rare cases, FedRAMP may determine the deficiency is severe enough to make the escalation effective immediately, in which case, steps 3 and 4 are skipped.</li>
	</ul>
</li>
<li><strong>FedRAMP notifies the CSP of the deficiency and FedRAMP’s intended escalation</strong>. Depending on the intended escalation level, the notice comes from:
	<ul>
<li>The FedRAMP POC for an intended DFR; or</li>
<li>The FedRAMP Director for an intended CAP, Suspension, or Revocation.</li>
	</ul></li>
<li><strong>The CSP responds to the notification.</strong> The CSP’s response should include any information that may rebut the escalation decision. Depending on the intended escalation level, the CSP’s response must come from:
	<ul>
<li>The CSP’s security POC for DFR; or</li>
<li>The CSP’s system owner for a CAP, Suspension, or Revocation.</li>
	</ul>
</li>
<li><strong>FedRAMP reviews and adjudicates the CSP’s response, and renders a formal escalation decision.</strong> Depending on the escalation level, the decision is made by:
<ul>
<li>The FedRAMP POC for a DFR;</li>
<li>The FedRAMP Director for a CAP; or</li>
<li>The JAB for a Suspension or Revocation.</li>
</ul>
</li>
<li><strong>FedRAMP notifies the CSP of its decision.</strong> If FedRAMP decides to follow through with an escalation, this notice:
	<ul>
<li>Identifies the criteria for returning the system to a “Satisfactory” status. It may also include a deadline by which the CSP must fully satisfy the criteria or face more severe escalation; and</li>
<li>Requires certain actions from the CSP. Typically, FedRAMP requires the CSP to perform a root-cause analysis and develop a formal plan for addressing the deficiencies.</li>
	</ul>
</li>
<li><strong>CSP responds to the FedRAMP notification.</strong> This response must include:
	<ul>
<li>The results of the root cause analysis;</li>
<li>The CSP’s plan for fully resolving the issues, with clearly established milestones and dates, including a date of full resolution;</li>
<li>For a CAP or Suspension, system owner signature on the plan and FedRAMP approval of the plan; and</li>
<li>Any other items as specified by FedRAMP in its notification.</li>
	</ul>
</li>
</ol>
 
<p>When a CSP is subject to escalation as described above, the following occurs:</p>
<ul>
<li><strong>Monthly ConMon Reporting to Leveraging Agencies:</strong> FedRAMP updates the next Monthly ConMon report to reflect the cited deficiencies, escalation level, and the CSP’s identified resolution date.</li>
<li>The system’s status is changed to “Minor Concern” for a DFR, or “Major Concern” for a CAP or Suspension. The status remains, and the CSP’s progress is reported each month until FedRAMP determines the issue is fully resolved.</li>
<li>FedRAMP discontinues ConMon reporting when the system’s P-ATO is suspended or revoked.</li>
<li><strong>Other Postings and Notifications to Leveraging Agencies:</strong> If there is a CAP, Suspension, or Revocation, FedRAMP posts a letter to its secure repository (OMB MAX) for review by leveraging Agencies, as is the CSP’s plan for resolution where appropriate. The information is retained indefinitely for historical reference.</li>
</ul>
<p>If a system’s P-ATO is suspended or revoked, FedRAMP notifies each known leveraging Agency directly, and requires the CSP to ensure the list of FedRAMP known leveraging Agencies matches the CSP’s customer list for the impacted system.</p>
<p><em>Note: P-ATO Revocation does not automatically result in revocation of each leveraging Agency’s ATO. Each leveraging Agency’s AO reviews the circumstances of P-ATO Revocation, and makes a determination regarding the status of the ATO they issued the system on behalf of their Agency.</em></p>
<ul>
<li><strong>FedRAMP Marketplace:</strong> FedRAMP updates the system’s status on the FedRAMP Marketplace at <a href="https://marketplace.fedramp.gov/">https://marketplace.fedramp.gov/</a> to reflect the escalation level for Suspension. FedRAMP removes the system from the Marketplace if the P-ATO is revoked. DFRs and CAPs are not reflected on the Marketplace.</li>
<li><strong>Further Escalation:</strong> If the CSP fails to provide a plan acceptable to FedRAMP, or fails to meet the dates identified in the plan, FedRAMP may increase the escalation level. Further escalation follows the escalation process steps described above.</li>
<li><strong>Extension:</strong> If the CSP has made a good-faith effort to fully resolve the deficiency and address the plan, but requires more time, the CSP may request an extension from FedRAMP.</li>
</ul>
<p>When FedRAMP determines the CSP has fully resolved the cited deficiencies and satisfied the FedRAMP-identified criteria communicated in the notification, FedRAMP takes the following actions:</p>
<ul>
<li><strong>Notification to CSP:</strong> The FedRAMP POC notifies the CSP’s security POC when FedRAMP agrees a DFR is fully satisfied. The FedRAMP Director notifies the system owner when FedRAMP agrees a CAP or Suspension is fully satisfied.</li>
<li><strong>Monthly ConMon Reporting to Leveraging Agencies:</strong> FedRAMP updates the next monthly report to reflect all cited deficiencies are resolved and the escalation level is no longer in effect. The status is returned to “Satisfactory.”</li>
<li><strong>Other Postings and Notifications to Leveraging Agencies:</strong> The FedRAMP Director posts a letter to the secure repository indicating the CAP or Suspension is fully resolved to FedRAMP’s satisfaction, and the CSP is once again in good standing. As no letter is posted when a DFR is initiated, no letter is posted when it is resolved.</li>
<li><strong>FedRAMP Marketplace:</strong> FedRAMP returns the system’s status to its normal listing with no indication of an escalation level.</li>
</ul>
</div>
<div id="risk-deficiency-triggers">
<h2>JAB ConMon Requirements: Risk Management Deficiency Triggers </h2>
<hr>
<p>To ensure consistent expectations and enforcement, FedRAMP defines risk management deficiency “triggers.” When a CSP’s performance exceeds one or more of the thresholds, defined in Table 1. JAB Risk Management Deficiency Triggers below, FedRAMP will, at a minimum, take the prescribed action.   </p>

<table>
<tbody>
<tr>
<th>
<strong>CONMON PROCESS AREA</strong>
</th>
<th>
<strong>RISK MANAGEMENT DEFICIENCY TRIGGER</strong>
</th>
<th>
<strong>MINIMUM ESCALATION LEVEL</strong>
</th>
</tr>
<tr>
<td rowspan="13" width="100">
<p><strong>Operational Visibility</strong></p>
</td>
<td width="380">
<p><strong>Unique Vulnerability Count Increase</strong></p>
<p><strong>20% from P-ATO baseline or 10 unique vulnerabilities, whichever is greater</strong></p>
<p><em>Note: A request to rebaseline a unique vulnerability count, accompanied with proper justification, can be submitted to FedRAMP and may be approved on a case by case basis.</em></p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Non-compliance with scanning requirements outlined in <em>FedRAMP Vulnerability Scanning Requirements</em> at</strong> <a href="https://www.fedramp.gov/documents/"><strong>https://www.fedramp.gov/documents/</strong></a></p>
<p><strong>First incident in the previous six months</strong></p>
<p>Unauthenticated scan results delivered as part of the initial SAR submission, as part of the annual SAR submission, or as part of the monthly scanning submission, where the unauthenticated scans are 10% or greater of the total scan submission, result in the CSP being placed on a DFR. This applies only to a CSP&rsquo;s first submission that is non-compliant with authenticated scan requirements.</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Non-compliance with scanning requirements outlined in <em>FedRAMP Vulnerability Scanning Requirements</em></strong></p>
<p><strong>Each subsequent incident beyond the first within the previous six months</strong></p>
<p>Unauthenticated scan results delivered as part of the initial SAR submission, as part of the annual SAR submission, or as part of the monthly scanning submission, where the unauthenticated scans are 10% or greater of the total scan submission, result in the CSP being placed on a CAP, when a second or subsequent CSP submission is non-compliant with authenticated scan requirements.</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation High Impact Vulnerabilities</strong></p>
<p>Five or more unique vulnerabilities or POA&amp;M items aged greater than 30 days</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation High Impact Vulnerabilities</strong></p>
<p>Five or more unique vulnerabilities or POA&amp;M items aged greater than 60 days</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation Moderate Impact Vulnerabilities</strong></p>
<p>Ten or more unique vulnerabilities or POA&amp;M items aged greater than 90 days</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation Moderate Impact Vulnerabilities</strong></p>
<p>Ten or more unique vulnerabilities or POA&amp;M items aged greater than 120 days</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Delivery of Annual Assessment SAP</strong></p>
<p>Delivery of annual assessment SAP less than 60 days before annual P-ATO anniversary date</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Delivery of Annual Assessment Package</strong></p>
<p>Delivery of full annual assessment package after annual P-ATO anniversary date</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Poor Quality of Deliverables</strong></p>
<p>Untimely or inaccurate submission of any deliverable, including (but not limited to) monthly ConMon documents, Deviation Requests, or Significant Change Requests</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Lack of Transparency</strong></p>
<p>Failure to report known issues to FedRAMP or purposely manipulating scans to avoid Risk Management Deficiency Triggers</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Multiple Recurrences</strong></p>
<p>Any trigger that is realized multiple times within a six-month timeframe</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Insufficient Notice of Planned Change</strong></p>
<p>Notification received less than 30 days before the planned change or insufficient documentation of the Security Impact Analysis</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td rowspan="3" width="100">
<p><strong>Change Control</strong></p>
</td>
<td width="380">
<p><strong>Late Notice of Emergency Change</strong></p>
<p>Notification received more than five days after the change</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Undocumented/Unreported Change:</strong></p>
<p>No notification</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Degradation of the Change Management and Change Control Processes</strong></p>
<p>Insufficient adherence to the provided Configuration Management Plan as determined by FedRAMP</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td rowspan="4" width="100">
<p><strong>Incident Response</strong></p>
</td>
<td width="380">
<p><strong>Late Incident Notification</strong></p>
<p>Late notification of incident not in accordance with the <em>FedRAMP Incident Communications Procedure</em> at <a href="https://www.fedramp.gov/documents/">https://www.fedramp.gov/documents/</a> and United States Computer Emergency Readiness Team (US-CERT) Federal Incident Notification Guidelines</p>
<p><em>Note:&nbsp; An incident is a violation of computer security policies, acceptable use policies, or standard computer security practices, according to NIST Special Publication 800-61, </em>Computer Security Incident Handling Guide<em>, Revision 2.</em></p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Incident Frequency of Recurring Type</strong></p>
<p>Any incident with recurring type and/or cause</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Incident Frequency</strong></p>
<p>Four or more incidents within six months</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Timely and Ongoing Notification of Zero-day Attack</strong></p>
<p>Failure to provide to FedRAMP daily updated progress in addressing zero-day attacks</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
</tbody>
</table>
</div>
<div id="customer-demand">
<h3>JAB Customer Demand   </h3>
<p>To remain eligible for a JAB P-ATO, FedRAMP requires a minimum of six unique Agency customers with authorizations[1] that leverage the system’s JAB P-ATO. FedRAMP evaluates CSP customer demand on a quarterly basis to ensure CSPs with P-ATOs are meeting and maintaining FedRAMP demand thresholds.</p>

<p>A CSP that has fewer than six unique FedRAMP ATOs posted on the FedRAMP secure repository will be placed on a CAP at the discretion of the FedRAMP Program Management Office (PMO) and JAB. A CSP that cannot meet or maintain this demand threshold has the opportunity to pursue FedRAMP Agency Authorizations, in lieu of the P-ATO, with the support of the FedRAMP PMO.</p>

<p>FedRAMP established this threshold based on JAB resources, to ensure JAB ConMon resources are focused on systems that result in broader impact across the Federal Government. FedRAMP may adjust this threshold at its discretion due to changes in available resources and overall demand across the Federal Government for cloud services.</p>
</div>
<div id="ato-performance-mgmt">
<h2>Agency ATO Performance Management </h2>
<hr>
</div>
<div id="agency-escalation-levels-process">
<h3>Agency Escalation Levels and Process </h3>
<p>Similar to JAB performance management of CSPs with P-ATOs, Agencies should implement an escalation process to monitor their authorized CSPs, which may result in one of the following escalation levels. Agency AOs can determine which escalation levels are appropriate:</p>
<ul>
<li><strong>Detailed Finding Review (DFR):</strong> A request from the Agency AO (or representative) for the CSP’s security POC to assess a deficiency, and report the cause and remedy back to the Agency AO. If the CSP does not resolve a DFR within the agreed upon timeframe, the Agency AO may escalate to a corrective action plan.</li>
<li><strong>Corrective Action Plan (CAP):</strong> A request from the Agency AO for the CSP’s system owner to perform a root-cause analysis and provide a formal plan for remediation. If the CSP does not resolve a CAP within the agreed upon timeframe, the Agency AO may suspend or revoke the system’s ATO.</li>
<li><strong>Suspension:</strong> A decision by the Agency AO to temporarily suspend a system’s ATO until identified deficiencies are resolved. In this phase, an Agency may choose to suspend new instance use of the system. If the CSP does not resolve a Suspension within the agreed upon timeframe, or if the Agency AO determines the CSP can no longer meet FedRAMP compliance requirements, the Agency AO may revoke the system’s ATO.</li>
<li><strong>Revocation:</strong> A decision by the Agency AO to revoke a system’s ATO and migrate the data to another system.</li>
</ul>
<p>When the Agency AO identifies a deficiency in the CSP’s ConMon capabilities, the Agency AO should initiate the escalation process described below.</p>
<p>The escalation process occurs as follows:</p>
<ol>
	<li><strong>The Agency AO identifies a deficiency with the CSP’s ConMon information.</strong></li>
<li><strong>The Agency AO reviews the deficiency and compares it to the CSP’s past ConMon performance.</strong> As a result of the review, the Agency AO decides on one of the following actions:
	<ul>
<li>The Agency AO may elect to simply monitor the CSP more closely and take no further action. If so, no notice is sent and the process stops here;</li>
<li>The Agency AO may increase a CSP’s existing escalation level. For example, a CSP on a CAP may face Suspension; or</li>
<li>The Agency AO may determine the deficiency is severe enough to make the escalation effective immediately, in which case, Steps 3 and 4 are skipped.</li>
	</ul></li>
<li>The Agency AO notifies the CSP of the deficiency and the Agency AO’s intended escalation.</li>
<li><strong>The CSP responds to the notification.</strong> The CSP’s response should include any information that may rebut the escalation decision. Depending on the intended escalation level, the CSP’s response must come from:
	<ul>
<li>The CSP’s security POC for a DFR; or</li>
<li>The CSP’s system owner for a CAP, Suspension, or Revocation.</li>
	</ul></li>
<li><strong>The Agency AO reviews and adjudicates the CSP’s response, and renders a formal escalation decision.</strong></li>
<li><strong>The Agency AO notifies the CSP of its decision.</strong> If the Agency AO decides to follow through with an escalation, this notice:
<ul>
<li>Identifies the criteria for returning the system to a “Satisfactory” status. It may also include a deadline by which the CSP must fully satisfy the criteria or face more severe escalation; and</li>
<li>Requires certain actions from the CSP. Typically, an Agency AO would require the CSP to perform a root-cause analysis and develop a formal plan for addressing the deficiencies.</li>
</ul></li>
<li><strong>The CSP responds to the Agency AO notification.</strong> This response must include:
<ul>
	<li>The results of the root cause analysis;</li>
<li>The CSP’s plan for fully resolving the issues, with clearly established milestones and dates, including a date of full resolution;</li>
<li>For a CAP or Suspension, system owner signature on the plan and Agency AO approval of the plan; and</li>
<li>Any other items as specified by the Agency AO in the notification.</li>
</ul></li>
</ol>
<p>When a CSP is subject to escalation as described above, the following occurs:</p>
<ul>
	<li><strong>Notification to FedRAMP:</strong> Agency AOs must notify FedRAMP at info@fedramp.gov if a decision is made to initiate Suspension or Revocation. Agency CAP letters should be posted to the FedRAMP secure repository.</li>
</ul>
<p>When the Agency AO determines the CSP has fully resolved the cited deficiencies and satisfied the identified criteria communicated in the notification, the Agency AO should take the following actions:</p>
<ul>
	<li><strong>Notification to FedRAMP:</strong> Agency AOs must notify FedRAMP at info@fedramp.gov if an escalation has been resolved. Agency CAP release letters should be posted to the FedRAMP secure repository.</li>
</ul>
</div>
<div id="agency-conmon-risk-mgmt-triggers">
<h2>Agency ConMon Requirements: Risk Management Deficiency Triggers   </h2>
<hr>
<p>To ensure consistent expectations and enforcement, an Agency AO should define risk management deficiency “triggers.” Example triggers are described in Table 2. Agency Risk Management Deficiency Triggers, below.</p>  
<p class="caption"><strong>Table 2. Agency  Risk Management Deficiency Triggers</strong></p>

<table>
<tbody>
<tr>
<th>
<strong>CONMON PROCESS AREA</strong>
</th>
<th>
<strong>RISK MANAGEMENT DEFICIENCY TRIGGER</strong>
</th>
<th>
<strong>MINIMUM ESCALATION LEVEL</strong>
</th>
</tr>
<tr>
<td rowspan="13" width="128">
<p><strong>Operational Visibility</strong></p>
</td>
<td>
<p><strong>Unique Vulnerability Count Increase</strong></p>
<p><strong>20% from ATO baseline or 10 unique vulnerabilities, whichever is greater</strong></p>
<p><em>Note: A request to rebaseline a unique vulnerability count, accompanied with proper justification, can be submitted to the AO and may be approved on a case by case basis.</span></em></p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Non-Compliance with scanning requirements</strong></p>
<p><strong>First incident in the previous six months</strong></p>
<p>Unauthenticated scan results delivered as part of the initial SAR submission, as part of the annual SAR submission, or as part of the monthly scanning submission, where the unauthenticated scans are 10% or greater of the total scan submission, result in the CSP being placed on a DFR. This applies only to a CSP&rsquo;s first submission that is non-compliant with authenticated scan requirements.</p>
</td>
<td>
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Non-Compliance with scanning requirements</strong></p>
<p><strong>Each subsequent incident beyond the first within the previous six months</strong></p>
<p>Unauthenticated scan results delivered as part of the initial SAR submission, as part of the annual SAR submission, or as part of the monthly scanning submission, where the unauthenticated scans are 10% or greater of the total scan submission, result in the CSP being placed on a CAP, when a second or greater CSP submission is non-adherent to authenticated scan requirements.&nbsp;&nbsp;</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation High Impact Vulnerabilities</strong></p>
<p>Five or more unique vulnerabilities or POA&amp;Ms aged greater than 30 days</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation High Impact Vulnerabilities</strong></p>
<p>Five or more unique vulnerabilities or POA&amp;Ms aged greater than 60 days</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation Moderate Impact Vulnerabilities</strong></p>
<p>Ten or more unique vulnerabilities or POA&amp;Ms aged greater than 90 days</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Remediation Moderate Impact Vulnerabilities</strong></p>
<p>Ten or more unique vulnerabilities or POA&amp;Ms aged greater than 120 days</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Delivery of Annual Assessment SAP</strong></p>
<p>Delivery of Annual Assessment SAP less than 60 days before annual ATO date</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Late Delivery of Annual Assessment Package</strong></p>
<p>Delivery of Annual Assessment ATO Package after ATO anniversary date</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Poor Quality of Deliverables</strong></p>
<p>Untimely or inaccurate submission of any deliverable, including (but not limited to) monthly ConMon documents, Deviation Requests, or Significant Change Requests</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Lack of Transparency</strong></p>
<p>Failure to report known issues to the AO or purposely manipulating scans to avoid Risk Management Triggers</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Multiple Recurrences</strong></p>
<p>Any trigger that is realized multiple times within a six-month timeframe</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Insufficient Notice of Planned Change</strong></p>
<p>Notification received less than 30 days before the planned change or insufficient documentation of the Security Impact Analysis</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td rowspan="3" width="128">
<p><strong>Change Control</strong></p>
</td>
<td>
<p><strong>Late Notice of Emergency Change</strong></p>
<p>Notification received longer than five days after the change</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Undocumented/Unreported Change</strong></p>
<p>No notification</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Degradation of the Change Management and Change Control Processes</strong></p>
<p>Insufficient adherence to the provided Configuration Management Plan as determined by the AO</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td rowspan="4" width="128">
<p><strong>Incident Response</strong></p>
</td>
<td width="380">
<p><strong>Late Incident Notification</strong></p>
<p>Late notification of incident not in accordance with the Incident Communications Procedure and United States Computer Emergency Readiness Team (US-CERT) Federal Incident Notification Guidelines</p>
<p><em>Note:&nbsp; An incident is a violation of computer security policies, acceptable use policies, or standard computer security practices, according to NIST Special Publication 800-61, </span></em>Computer Security Incident Handling Guide</span><em>, Revision 2.</span></em></p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Incident Frequency of Recurring Type</strong></p>
<p>Any incident with recurring type and/or cause</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Incident Frequency</strong></p>
<p>Four or more incidents within six months</p>
</td>
<td width="128">
<p>DFR</p>
</td>
</tr>
<tr>
<td width="380">
<p><strong>Timely and Ongoing Notification of Zero-day Attack</strong></p>
<p>Failure to provide to the AO daily updated progress in addressing zero-day attacks</p>
</td>
<td width="128">
<p>CAP</p>
</td>
</tr>
</tbody>
</table>

</div>
<div id="fedramp-for-agency-atos">
<h3>FedRAMP Responsibilities for Agency ATOs   </h3>
<p>The FedRAMP PMO monitors Agency ATO packages to ensure that the service remains in good standing. Specifically, FedRAMP ensures:</p>
<ul>
<li>The annual assessment package is uploaded and complete;</li>
<li>The latest SAR recommends continued authorization; and</li>
<li>The FedRAMP Marketplace and repository appropriately reflects authorization, suspension and revocation status.</li>
</ul>
</div>