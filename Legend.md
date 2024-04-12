```plantuml
@startuml
title Legend
!include https://raw.githubusercontent.com/JohnLeyva/plantuml-assets/master/style-base.puml
$legend()
@enduml
```

```plantuml
@startuml
title Conventions
'skinparam linetype ortho
'!theme spacelab
!include https://raw.githubusercontent.com/JohnLeyva/plantuml-assets/master/style-simple.puml
'$example_style()
@enduml
```


```plantuml
@startuml
colors
@enduml
```

```plantuml
@startuml
listopeniconic
@enduml
@startuml
card c [     
    [[https://plantuml.com/openiconic]] 
     ]
@enduml
```


```plantuml
@startuml
scale .5
!include <osa/user/audit/audit>
'beware of 'hat-sprite'
!include <osa/user/black/hat/hat-sprite>
!include <osa/user/blue/blue>
!include <osa/user/blue/security/specialist/specialist>
!include <osa/user/blue/sysadmin/sysadmin>
!include <osa/user/blue/tester/tester>
!include <osa/user/blue/tie/tie>
!include <osa/user/green/architect/architect>
!include <osa/user/green/business/manager/manager>
!include <osa/user/green/developer/developer>
!include <osa/user/green/green>
!include <osa/user/green/operations/operations>
!include <osa/user/green/project/manager/manager>
!include <osa/user/green/service/manager/manager>
!include <osa/user/green/warning/warning>
!include <osa/user/large/group/group>
!include <osa/users/blue/green/green>
!include <osa/user/white/hat/hat>


'!define osaPuml https://raw.githubusercontent.com/Crashedmind/PlantUML-opensecurityarchitecture2-icons/master
'!include osaPuml/Common.puml
'!include osaPuml/User/all.puml

!include <office/Servers/database_server>
!include <office/Servers/file_server>
!include <office/Servers/application_server>
!include <office/Concepts/service_application>
!include <office/Concepts/firewall>


listsprites

@enduml
```



