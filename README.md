# EDEN-News
TP Évaluation - EDEN News - Erylenn | Marina Bailleul | 2ème Année

## Organisation pour le TP Évaluation EDEN News

- Github ✅
- Reprendre l'ancien code de l'arborescence MVC ( Mobiliers ) ✅
    - Modifier les fichiers et le contenu qui n'a pas de rapport avec le TP
    - Rajouter le SCSS, ( utilisation de SASS ) ✅
- Modéliser la base de données : ✅
____________________________________________________________________________________________________________

    tbl_users : 
                - user_id 🔑 | ⛓ | 🔧 | 1️⃣
                - role_id
                - email 🔤
                - username 🔤
                - password 🔤 

    tbl_articles :
                    - art_id 🔑 | 🔧 | 1️⃣
                    - user_id  ⛓ | 1️⃣ 
                    - cat_id 1️⃣ | ⛓
                    - art_title 🔤
                    - art_slug 🔤
                    - art_content 🔤
                    - art_desc ( Jsp )
                    - art_img 🔤
                    - art_status
                    - updated_at
                    - created_at ⏲️
    
     tbl_category :
                    - cat_id 🔑 | 🔧 | 1️⃣ | ⛓
                    - cat_name
                    - created_at ⏲️

    tbl_sub_category :
                    - sub_cat_id 🔑 | 🔧 | 1️⃣
                    - cat_id 1️⃣
                    - art_id 1️⃣
                    - sub_cat_name
                    - created_at ⏲️

    tbl_comments :
                    - comment_id 🔑 | 🔧 | 1️⃣
                    - user_id ⛓ | 1️⃣
                    - comment_content 🔤
                    - created_at ⏲️
            
____________________________________________________________________________________________________________
                                                                                                            
- Initialiser la BDD ✅                                                                                       
- Faire le front :)                                                                                         
        __MOBILE FIRST__                                                                                    
                                                                                                            
    - Faire des variables pour la CG                                                                        
    - Link les links                                                                                        
    - Faire le header & le footer en premier                                                                
    - Ne pas mettre 3h pour des images et des catégories :-)                                                
                                                                                                            
____________________________________________________________________________________________________________

## LAST UPDATE 11/02/2021 | 09:50AM
