```
(define-constant MY_NAME "CiaraMaria aka mariaverse")
(define-constant MY_PASSION "helping to build a user owned web3 on Stacks.")

(define-read-only (get-greeting)
  (let 
    (
      (name (concat "Hi my name is " MY_NAME))
      (passion (concat ", and I am " MY_PASSION))
    )
    (print (concat name passion))
  )
)
```
