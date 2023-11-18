
Group Policy Objects (GPOs), werden in folgender Reihenfolge ausgeführt. 

1. Lokale Gruppenrichtlinien (Local GPO): Werden zuerst angewendet und sind spezifisch für die lokale Maschine.
2. Standortverknüpfte GPOs: Werden auf die Active Directory-Standorte angewendet.
3. Domänenverknüpfte GPOs: Werden auf die gesamte Domäne angewendet.
4. Organizational Unit (OU)-verknüpfte GPOs: Werden auf spezifische OUs innerhalb der Domäne angewendet.

GPOs, die hierarchisch näher am Ziel liegen (d.h., OUs näher am Benutzer oder Computer), haben Vorrang vor GPOs, die auf höheren Ebenen verknüpft sind. Innerhalb jeder Ebene werden GPOs in einer festgelegten Reihenfolge verarbeitet, wobei die zuletzt angewendete GPO Vorrang hat, falls es zu Konflikten bei den Einstellungen kommt.