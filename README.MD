es1
SELECT \*
FROM
`students`
WHERE
`enrolment_date` LIKE '2020%';

es2
SELECT \*
FROM
`teachers`
WHERE
`office_address` = 'Contrada Penelope 73';

es3
SELECT
AVG( `vote` )
FROM
`exam_student`;
