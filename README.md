# R-chapter-4-5
R studio
! tidy verse 작동후...
ggplot() 함수로 플롯을 시작한다. ggplot() 을 하면 좌표시스템이 생성되고 레이어를 추가할 수 있다. 
 
 ex) 
 ggplot(data = <DATA>) + 
  <GEOM_FUNCTION>(mapping = aes(<MAPPINGS>))
    
geom_point = 산점도 표시!
    
 ex) ggplot(data = mpg) + 
  geom_point(mapping = aes(x = displ, y = hwy, color = class))
    
    
