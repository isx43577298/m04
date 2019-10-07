# Exercicis Git  

__Nivell 1 Intro__  
![intro](
https://github.com/isx43577298/m04/blob/master/nivel1.png?raw=true)  

__Resposta__  

> git commit  
git commit


__Nivell 2 Intro__  

![intro](https://github.com/isx43577298/m04/blob/master/nivel2.png?raw=true)  

__Resposta__  

> git branch bugFix  
git checkout bugFix


__Nivell 3 Intro__  

![intro](https://github.com/isx43577298/m04/blob/master/nivel%203.png?raw=true)
__Resposta__  

> git checkout -b bugFix  
git commit  
git checkout master  
git commit  
git merge bugFix  


__Nivell 4 Intro__

![intro](https://github.com/isx43577298/m04/blob/master/nivell4.png?raw=true)
__Resposta__  
> git checkout -b bugFix  
git commit  
git checkout master  
git commit  
git checkout bugFix  
git rebase master  


__Nivell 1 Rampup__  
![rampup](https://github.com/isx43577298/m04/blob/master/nivell1_fase2.png?raw=true)

__Resposta__  
> git checkout c4  

__Nivell 2 Rampup__  
![rampup](https://github.com/isx43577298/m04/blob/master/nivell2_fase2.png?raw=true)
__Resposta__  
> git checkout bugFix^  

__Nivell 3 Rampup__  
![rampup](https://github.com/isx43577298/m04/blob/master/nivell3_fase2.png?raw=true)
__Resposta__  
> git checkout HEAD^  
git branch -f bugFix HEAD^  
git branch -f master c6  


__Nivell 4 Rampup__  
![rampup](https://github.com/isx43577298/m04/blob/master/nivell4_fase2.png?raw=true)
__Resposta__  
>git branch -f local c1  
git checkout pushed  
git revert pushed

__Nivell 1 Move__  
![move](https://github.com/isx43577298/m04/blob/master/nivell1_fase3.png?raw=true)
__Resposta__  
> git cherry-pick c3 c4 c7  

__Nivell 2 Move__  
![move](https://github.com/isx43577298/m04/blob/master/nivell2_fase3.png?raw=true)

__Resposta__  
> git revase -i HEAD~4  

__Nivell 1 mixed__  
![mixed](https://github.com/isx43577298/m04/blob/master/nivell1_fase4.png?raw=true)
__Resposta__  
> git checkout master  
git branch -f master c4  
git rebase -i HEAD~3  
Resposta web -> git rebase -i master ; git rebase bugFix master  


__Nivell 2 mixed__  
![mixed](https://github.com/isx43577298/m04/blob/master/nivell2_fase4.png?raw=true)
__Resposta__  
> $ git rebase -i master  
git commit --amend  
git rebase -i master  
git rebase caption master  

__Nivell 3 mixed__  
![mixed](https://github.com/isx43577298/m04/blob/master/nivell3_fase4.png?raw=true)

__Resposta__  
>  git checkout master  
git cherry-pick c2  
git cherry-pick c3

__Nivell 4 mixed__  
![mixed](https://github.com/isx43577298/m04/blob/master/nivell4_fase4.png?raw=true)
__Resposta__  

> git tag v0 c1  
git tag v1 c2  
git checkout c2  

__Nivell 5 mixed__  
![mixed](https://github.com/isx43577298/m04/blob/master/nivell5_fase4.png?raw=true)
__Resposta__  
> git commit  
