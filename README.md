<div position="relative" text-align="center">
    <a href="https://cloudflare-ipfs.com/ipfs/bafykbzaceazqyuzws24egw3frzo46filybgd35ma6x4uxwfewcadh7pty3jym?filename=(Collection%20%C2%ABCritique%C2%BB)%20Deleuze%20-%20Mille%20Plateaux-Les%20%C3%89ditions%20de%20Minuit%20(1998).pdf#page=3">
    	<!-- Grande Sertão: Veredas by Poty Lazzarotto. -->
        <img src="https://raw.githubusercontent.com/gbrlgn/gbrlgn/main/nonada.png">
    </a>
<div>

```clojure
(ns github.readme
  (:require [earth.human :as user]))

(defn bio
  [user]
  (let [inf {:name "Gabriel Gian"
             :location "Minas Gerais, Brasil"
             :interests #{"AI" "Development" "Free Software" "Operations"}}
        dev {:langs ["Bash" "Clojure" "Go" "Java" "Python" "Rust" "SQL" "TypeScript"]
             :tools ["Babashka" "Emacs" "IDEA" "PyCharm"]}
        ops {:os #{"NixOS"}
             :iac ["Ansible" "Terraform" "Vagrant"]
             :ci-cd ["Docker" "GitLab CI" "Jenkins" "Kubernetes"]
             :cloud #{"AWS" "GCP" "OCI"}
             :db #{"DynamoDB" "PostgreSQL" "Redis"}}]
    (->> user
         (build-user inf)
         (test-user dev)
         (deploy-user ops))))

(bio user/gbrlgn)
```
<div position="relative" text-align="center">
    <a href="https://cloudflare-ipfs.com/ipfs/bafykbzaceazqyuzws24egw3frzo46filybgd35ma6x4uxwfewcadh7pty3jym?filename=(Collection%20%C2%ABCritique%C2%BB)%20Deleuze%20-%20Mille%20Plateaux-Les%20%C3%89ditions%20de%20Minuit%20(1998).pdf#page=388">
    	<!-- Grande Sertão: Veredas by Poty Lazzarotto. -->
        <img src="https://raw.githubusercontent.com/gbrlgn/gbrlgn/main/travessia.png">
    </a>
<div>
