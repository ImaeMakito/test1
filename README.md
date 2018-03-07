select distinct ename,deptno
from emp
where deptno in (
  select deptno
  from dept
  where dname like '%S%'
  )

  select *
  from
  limit 1000
  jjj
  
