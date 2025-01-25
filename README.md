# Decentralized Negotiation Protocol for Collaborative Collision Avoidance of ASVs
Simulation and field test results of the paper called "A Decentralized Negotiation Protocol for Collaborative Collision Avoidance of Autonomous Surface Vehicles".

---

A selection of scenarios illustrated in tables below, has been chosen to evaluate the proposed negotiation protocol. These scenarios encompass various cases such as head-on, crossing, and overtaking responsibilities for vehicles. 

Each vehicle is assigned distinct profiles to depict homogeneous and heterogeneous characteristics. In homogeneous scenarios, vehicles share identical collision avoidance algorithm (SB-MPC) alongside the same collision avoidance initialization and safe distance parameters. Conversely, heterogeneous vehicles utilize SB-MPC and RVO collision avoidance algorithms and are configured with different initialization and safe distance parameters. Vehicles utilizing the SB-MPC algorithm are represented in blue, while those employing the RVO algorithm are shown in orange. 

First columns of the tables illustrate the benchmark scenarios involving homogeneous vehicles employing the SB-MPC algorithm without collaboration. Second columns present scenarios involving homogeneous vehicles equipped with collaborative SB-MPC algorithms. Collaborative heterogeneous vehicles with different collision avoidance algorithms and parameters are defined in third columns where the larger vehicles represent bigger initialization and safe distance parameters. The initialization and safe distance parameters are set as 150 m and 20 m in default and 200 m and 30 m for bigger vehicles in heterogeneous vehicle scenarios. Some scenarios demonstrate a more complex case involving both collaborative (blue and orange), non-collaborative (white with blue borderline), and non-cooperative (gray) heterogeneous vehicles. 

Each scenario is simulated five times, and some field tests have been conducted multiple times as well. The figures in the tables below represent only a single trial result of coordinate plot. To review all trials with additional visualizations, please refer to the corresponding section. 

---

## Simulation results

<div style="text-align: center;">
  <table style="width: 100%; border-collapse: collapse; table-layout: fixed;">
    <!-- Scenario 1: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/01_noncollab_scenarios_01.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 1: SB-MPC without collaboration.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_01.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 1: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_01.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 1: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 1: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario01/01_Benchmark_SBMPC_without_collab" target="_blank">
          <img src="01_simulation_results/Scenario01/01_Benchmark_SBMPC_without_collab/01/scenario_xy_coord.png" alt="Bechmark SB-MPC" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario01/02_CollabHomogen" target="_blank">
          <img src="01_simulation_results/Scenario01/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario01/03_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario01/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 2: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/01_noncollab_scenarios_02.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 2: SB-MPC without collaboration.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_02.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 2: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_02.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 2: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 2: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario02/01_Benchmark_SBMPC_without_collab" target="_blank">
          <img src="01_simulation_results/Scenario02/01_Benchmark_SBMPC_without_collab/01/scenario_xy_coord.png" alt="Bechmark SB-MPC" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario02/02_CollabHomogen" target="_blank">
          <img src="01_simulation_results/Scenario02/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario02/03_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario02/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 3: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/01_noncollab_scenarios_03.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 3: SB-MPC without collaboration.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_03.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 3: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_03.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 3: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 3: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario03/01_Benchmark_SBMPC_without_collab" target="_blank">
          <img src="01_simulation_results/Scenario03/01_Benchmark_SBMPC_without_collab/01/scenario_xy_coord.png" alt="Bechmark SB-MPC" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario03/02_CollabHomogen" target="_blank">
          <img src="01_simulation_results/Scenario03/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario03/03_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario03/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 4: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/01_noncollab_scenarios_04.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 4: SB-MPC without collaboration.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_04.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 4: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_04.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 4: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 4: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario04/01_Benchmark_SBMPC_without_collab" target="_blank">
          <img src="01_simulation_results/Scenario04/01_Benchmark_SBMPC_without_collab/01/scenario_xy_coord.png" alt="Bechmark SB-MPC" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario04/02_CollabHomogen" target="_blank">
          <img src="01_simulation_results/Scenario04/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario04/03_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario04/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/01_noncollab_scenarios_05.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: SB-MPC without collaboration.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_05.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_05.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario05/01_Benchmark_SBMPC_without_collab" target="_blank">
          <img src="01_simulation_results/Scenario05/01_Benchmark_SBMPC_without_collab/01/scenario_xy_coord.png" alt="Bechmark SB-MPC" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario05/02_CollabHomogen" target="_blank">
          <img src="01_simulation_results/Scenario05/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario05/03_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario05/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5/6: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/04_noncollab_asym_scenario.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative and non-collaborative collision avoidance between heterogenous vesses (SB-MPC, RVO, and SB-MPC (without collab)).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/05_noncoop_asym_scenario.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative collision avoidance between heterogenous vesses with non-cooperative vessel in the environment (SB-MPC, RVO, and non-coop. vessel).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/06_asym_noncollab_scenario.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 6: Mixed scenario (collab SB-MPC, collab RVO, non-collab SB-MPC, and non-coop vessels).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5/6: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario05/04_CollabAndNonCollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario05/04_CollabAndNonCollabHeterogen/01/scenario_xy_coord.png" alt="Collab And NonCollab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario05/05_CollabAndNonCoopHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario05/05_CollabAndNonCoopHeterogen/01/scenario_xy_coord.png" alt="Collab And NonCoop Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/01_simulation_results/Scenario06/01_CollabAndNonCoopHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario06/01_CollabAndNonCoopHeterogen/01/scenario_xy_coord.png" alt="Mixed scenario" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
  </table>
<div>


---


## Field test results

<div style="text-align: center;">
  <table style="width: 100%; border-collapse: collapse; table-layout: fixed;">
    <!-- Scenario 1: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_01.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 1: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_01.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 1: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 1: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario01/01_CollabHomogen/01" target="_blank">
          <img src="01_simulation_results/Scenario01/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario01/02_CollabHeterogen/01" target="_blank">
          <img src="01_simulation_results/Scenario01/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 2: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_02.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 2: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_02.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 2: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 2: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario02/01_CollabHomogen/01" target="_blank">
          <img src="01_simulation_results/Scenario02/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario02/02_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario02/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 3: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_03.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 3: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_03.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 3: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 3: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario03/01_CollabHomogen/01" target="_blank">
          <img src="01_simulation_results/Scenario03/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario03/02_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario03/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 4: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_04.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 4: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_04.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 4: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 4: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario04/01_CollabHomogen/01" target="_blank">
          <img src="01_simulation_results/Scenario04/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario04/02_CollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario04/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/02_sym_collab_scenarios_05.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative homogenous vessels (collaborative SB-MPC).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/03_asym_collab_scenarios_05.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative heterogenous vessels (collaborative SB-MPC and RVO).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario05/01_CollabHomogen/01" target="_blank">
          <img src="01_simulation_results/Scenario05/02_CollabHomogen/01/scenario_xy_coord.png" alt="Collab Colav Homogenous" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario05/02_CollabHeterogen/01" target="_blank">
          <img src="01_simulation_results/Scenario05/03_CollabHeterogen/01/scenario_xy_coord.png" alt="Collab Colab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5: Definition -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/04_noncollab_asym_scenario.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative and non-collaborative collision avoidance between heterogenous vesses (SB-MPC, RVO, and SB-MPC (without collab)).</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/00_scenario_definitions" target="_blank">
          <img src="00_scenario_definitions/05_noncoop_asym_scenario.png" alt="Scenario definition" width="100"/>
          <p><em>Scenario 5: Collaborative collision avoidance between heterogenous vesses with non-cooperative vessel in the environment (SB-MPC, RVO, and non-coop. vessel).</em></p>
        </a>
      </td>
    </tr>
    <!-- Scenario 5: Results -->
    <tr>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario05/03_CollabNonCollabHeterogen" target="_blank">
          <img src="01_simulation_results/Scenario05/04_CollabAndNonCollabHeterogen/01/scenario_xy_coord.png" alt="Collab And NonCollab Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
      <td style="text-align: center; vertical-align: middle;">
        <a href="https://github.com/MelihAkdag/Decentralized-Negotiation-Protocol-for-Collaborative-Collision-Avoidance-of-ASVs-Results/tree/main/02_field_test_results/Scenario05/04_CollabNonCoopHeterogen/01" target="_blank">
          <img src="01_simulation_results/Scenario05/05_CollabAndNonCoopHeterogen/01/scenario_xy_coord.png" alt="Collab And NonCoop Hetero" width="400"/>
          <p><em>Click for more results.</em></p>
        </a>
      </td>
    </tr>
  </table>
<div>



---

## Contact

For any questions or issues, feel free to reach out to **Melih Akdağ** at **akdag.melih@gmail.com**.
