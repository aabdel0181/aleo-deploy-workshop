# Aleo Deployment Demo
### Build & Test our Program

My demo results: 

1. Does it build? `leo build`
   `Leo ✅ Compiled 'main.leo' into Aleo instructions`
2. Can we mint tokens? `leo run mint`
   Result: ![image](https://github.com/aabdel0181/aleo-deploy-workshop/assets/68669398/32d4f7ab-d288-4c4a-84d9-2fd76799180c)
3. Can we transfer tokens? `leo run transfer`

```craigjohnson@home deploy_workshop % leo run transfer
       Leo ✅ Compiled 'main.leo' into Aleo instructions

⛓  Constraints

 •  'deploy_workshop.aleo/transfer' - 4,075 constraints (called 1 time)

➡️  Outputs Transfer

```
My output: ![image](https://github.com/aabdel0181/aleo-deploy-workshop/assets/68669398/2820ddfd-5817-495c-bf4f-cdde4d566375)


You can see here, one account now has 90 tokens and the other has 10, meaning we succesfully transfered 10 tokens.
