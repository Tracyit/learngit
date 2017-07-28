Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
My stupid boss still prefers SVN.
Creating a new branch is quick.
Creating a new branch is quick Test.
SELECT *
FROM   hr_operating_units t
WHERE  t.organization_id  IN (SELECT DISTINCT t.organization_id
        FROM   mtl_onhand_quantities t)