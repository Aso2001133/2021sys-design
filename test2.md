```uml
  @startuml
  start
  :体力=10;
  if(体力<=20)then(true)
    :宿谷に泊まる;
elsethen(false)
  :頑張ってレベルを上げる;
endif
  
  end
  @enduml
