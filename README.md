# ipp5-frontend-launcher

~~~~~ sh
npm install e53e04ac/ipp5-frontend-launcher
~~~~~

~~~~~ mjs
import { Ipp5FrontendLauncher } from 'ipp5-frontend-launcher';
~~~~~

~~~~~ mermaid
graph RL;
  A["package.json\npackage-lock.json"];
  subgraph "dependencies";
    B_0(["azure-terraformer"]);
    B_1(["event-emitter"]);
    B_2(["file-entry-native"]);
    B_3(["hold"]);
    B_4(["ipp5-types"]);
  end;
  subgraph "devDependencies";
    B_5(["@types/node"]);
    B_6(["file-entry"]);
  end;
  subgraph "github";
    C_0(["e53e04ac/azure-terraformer\n16560692233a91b14cc61b3efbf82150630ab55d"]);
    C_1(["e53e04ac/event-emitter\nf8600a5c4de347aa3374c8a40ea315afdcde0d3b"]);
    C_2(["e53e04ac/file-entry-native\nb94b164f9736e25ddadef6259b20fb58e9119c3a"]);
    C_3(["e53e04ac/hold\ndb62bd33b4c93d0fb459b06c3b707d82924c6077"]);
    C_4(["e53e04ac/ipp5-types\n4c73ee58032582f110121a843d04662ab3e4acbb"]);
    C_6(["e53e04ac/file-entry\n860fe9c95d090bea1b0b44c885aabb3b44733b47"]);
  end;
  subgraph "npmjs";
    C_5(["@types/node\n18.14.6"]);
  end;
  A ----> B_0;
  A ----> B_1;
  A ----> B_2;
  A ----> B_3;
  A ----> B_4;
  A ----> B_5;
  A ----> B_6;
  B_0 ----> C_0;
  B_1 ----> C_1;
  B_2 ----> C_2;
  B_3 ----> C_3;
  B_4 ----> C_4;
  B_5 ----> C_5;
  B_6 ----> C_6;
  click C_0 "https://github.com/e53e04ac/azure-terraformer/tree/16560692233a91b14cc61b3efbf82150630ab55d";
  click C_1 "https://github.com/e53e04ac/event-emitter/tree/f8600a5c4de347aa3374c8a40ea315afdcde0d3b";
  click C_2 "https://github.com/e53e04ac/file-entry-native/tree/b94b164f9736e25ddadef6259b20fb58e9119c3a";
  click C_3 "https://github.com/e53e04ac/hold/tree/db62bd33b4c93d0fb459b06c3b707d82924c6077";
  click C_4 "https://github.com/e53e04ac/ipp5-types/tree/4c73ee58032582f110121a843d04662ab3e4acbb";
  click C_5 "https://www.npmjs.com/package/@types/node/v/18.14.6";
  click C_6 "https://github.com/e53e04ac/file-entry/tree/860fe9c95d090bea1b0b44c885aabb3b44733b47";
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/ipp5-frontend-launcher";
    E_0(["namespace Ipp5FrontendLauncher"]);
    E_1(["type Ipp5FrontendLauncher"]);
    E_2(["const Ipp5FrontendLauncher"]);
  end;
  M["index.d.ts"]
  subgraph "azure-terraformer";
    I_0_0(["AzureTerraformer"]);
  end;
  subgraph "event-emitter";
    I_1_0(["EventEmitter"]);
  end;
  subgraph "file-entry";
    I_2_0(["FileEntry"]);
  end;
  subgraph "hold";
    I_3_0(["Get"]);
    I_3_1(["ValueOrGet"]);
  end;
  subgraph "ipp5-types";
    I_4_0(["Ipp5FrontendEnvMap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_2_0;
  M ----> I_3_0;
  M ----> I_3_1;
  M ----> I_4_0;
  E_0 ----> M;
  E_1 ----> M;
  E_2 ----> M;
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/ipp5-frontend-launcher";
    E_0(["Ipp5FrontendLauncher"]);
  end;
  M["index.mjs"]
  subgraph "azure-terraformer";
    I_0_0(["AzureTerraformer"]);
  end;
  subgraph "event-emitter";
    I_1_0(["EventEmitter"]);
  end;
  subgraph "file-entry-native";
    I_2_0(["FileEntry"]);
  end;
  subgraph "hold";
    I_3_0(["hold"]);
    I_3_1(["unwrap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_2_0;
  M ----> I_3_0;
  M ----> I_3_1;
  E_0 ----> M;
~~~~~
