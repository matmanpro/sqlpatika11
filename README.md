# sqlpatika11
(select vchNotes,idAMDossier from tblAMDossier)
except
(select Remark,idEmployee from tblProject)



(select first_name from actor)
intersect
(select first_name from customer)


(select first_name from actor)
except
(select first_name from customer)
