# Threat-Hunting-Detection
 <h3> Executive Summary</h3>  
<p>
This report presents the findings of a structured threat intelligence engagement targeting the insurance and financial services sector, conducted using the MITRE ATT&CK framework and the SOCRadar.io threat intelligence platform. The engagement was designed to fulfil three core threat intelligence responsibilities: leveraging MITRE ATT&CK to identify and analyse adversary tactics, techniques, and procedures (TTPs) to strengthen detection capabilities; developing a proactive threat hunting posture through intelligence-led identification of emerging attack paths and security gaps; and producing tactical, operational, and strategic threat intelligence specific to the insurance and financial services sectors.</p>
Seven advanced persistent threat (APT) groups were identified, researched, and profiled: four nation-state actors (APT41, LAZARUS GROUP, KIMSUKY, SANDWORM) and three financially motivated threat actor clusters (FIN7/Carbanak, TA505/Clop, Scattered Spider/UNC3944). All seven groups have documented targeting of financial institutions, insurers, or adjacent sectors with high-impact operations including financial theft, ransomware deployment, data exfiltration, and critical infrastructure disruption.
The MITRE ATT&CK Navigator was used to create individual technique layers for each APT and generate a composite overlap layer — revealing that 12 of 15 ATT&CK tactic categories are shared by five or more of the seven profiled actors. </p>
This convergence has a direct operational implication: detection rules and hunting queries targeting the highest-overlap techniques will provide adversary-agnostic coverage effective against the majority of the identified threat landscape, regardless of which specific actor initiates an attack.
The report concludes with prioritised detection engineering recommendations, proactive threat hunting use cases specific to the financial services sector, and a strategic intelligence assessment of the evolving threat landscape.
</li> 
 </h3>Intelligence Objectives & Responsibility Alignment</h3>
 
</h3>This engagement was structured to provide direct evidence against three core threat intelligence responsibilities. The table below maps each responsibility to the specific activities and outputs produced in this report.</h3>
