<div position="relative" text-align="center">
    <a href="http://classiques.uqac.ca/classiques/weil_simone/pesanteur_et_grace/pesanteur_et_grace.pdf#page=39">
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
        dev {:langs ["Bash" "Clojure" "Go" "Java" "Python" "Rust" "TypeScript"]
             :tools ["Babashka" "Emacs" "IDEA" "PyCharm" "VSCodium"]}
        ops {:os #{"Fedora" "NixOS" "Ubuntu"}
             :iac ["Ansible" "Terraform" "Vagrant"]
             :cont ["containerd" "Docker" "Kubernetes"]
             :ci-cd ["Argo CD" "Jenkins" "Rancher"]
             :cloud #{"AWS" "GCP" "OCI"}
             :db ["DynamoDB" "MongoDB" "PostgreSQL" "Redis"]}]
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
