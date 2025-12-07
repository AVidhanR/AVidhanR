<a href="https://linkedin.com/in/AVidhanR" target="_blank"><img src="https://img.shields.io/badge/follow%20me%20on%20LinkedIn-0A66C2" alt="itsvidhanreddy" /></a> <a href="https://x.com/itsvidhanreddy" target="_blank"><img src="https://img.shields.io/twitter/follow/itsvidhanreddy?label=@itsvidhanreddy&style=social" alt="X"></a>

```sql
/* ===========================================================
   Author: A. Vidhan Reddy
   Role  : Oracle Fusion Data Intelligence Developer
   =========================================================== */

CREATE OR REPLACE PROCEDURE about_vidhan_reddy
IS
    v_name            VARCHAR2(100) := 'A. Vidhan Reddy';

    v_education       VARCHAR2(300) :=
        'B.Tech in Computer Science Engineering (Honors), ' ||
        'Raghu Engineering College | CGPA: 9.42';

    v_current_role    VARCHAR2(200) :=
        'Programmer Analyst Trainee @ Cognizant Technology Solutions';

    v_specialization  VARCHAR2(400) :=
        'Oracle Fusion Data Intelligence (FDI), ' ||
        'Oracle Cloud Infrastructure – Data Integration (OCI-DI), ' ||
        'Oracle SQL & PL/SQL';

    TYPE tech_stack_t IS TABLE OF VARCHAR2(100);

    v_oracle_stack     tech_stack_t := tech_stack_t(
        'SQL', 'PL/SQL', 'FDI', 'OCI-DI', 'OBIEE', 'ODI Studio', 'OAC'
    );

    v_programming     tech_stack_t := tech_stack_t(
        'Python', 'JavaScript', 'HTML', 'CSS'
    );

    v_tools_concepts  tech_stack_t := tech_stack_t(
        'Git', 'Generative AI Tools', 'OOP', 'Cloud Analytics'
    );

    v_certifications  tech_stack_t := tech_stack_t(
        'OCI Foundations Associate',
        'Oracle Fusion Data Intelligence – Oracle University',
        'Linux Unhatched – Cisco Networking Academy & NDG',
        'HTML, CSS, JavaScript, Python – Codedex',
        'SQL – HackerRank'
    );

    v_interests       VARCHAR2(300) :=
        'Building scalable data-driven solutions, ' ||
        'cloud analytics, continuous learning, ' ||
        'solving real-world problems';

BEGIN
    NULL; -- Profile initialized successfully
END about_vidhan_reddy;
/
```
