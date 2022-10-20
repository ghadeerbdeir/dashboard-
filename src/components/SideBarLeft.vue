<template>
  <!--div class="container">
    <nav class="sidebar">
      <div class="position-sticky">
        <div class="list-group list-group-flush mx-3 mt-4">
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-house me-3"></h3>
          </a>
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-file-bar-graph me-3"></h3>
          </a>
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-file-bar-graph me-3"></h3>
          </a>
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-file-bar-graph me-3"></h3>
          </a>
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-file-bar-graph me-3"></h3>
          </a>
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-file-bar-graph me-3"></h3>
          </a>
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-file-bar-graph me-3"></h3>
          </a>
          <a class="py-2 text-white" href="#">
            <h3 class="bi bi-file-bar-graph me-3"></h3>
          </a>
          <a class="setting py-5 text-white" href="#">
            <h3 class="bi bi-gear me-3"></h3>
          </a>
        </div>
      </div>
    </nav>
  </div-->
  <div class="container-fluid">
    <div class="row flex-nowrap">
      <div class="col-auto col-md-3 col-xl-2 px-sm-2 px-0">
        <div
          class="
            d-flex
            flex-column
            align-items-center align-items-sm-start
            px-3
            pt-2
            text-white
          "
          style="
            background-color: #716cf8;
            border-radius: 25px;
            position: fixed;
            left: 2rem;
            top: 2rem;
            height: 860px;
          "
        >
          <a
            href="/"
            class="d-block p-3 text-white text-decoration-none"
            title=""
            data-bs-toggle="tooltip"
            data-bs-placement="right"
            data-bs-original-title="Icon-only"
          >
            <i class="bi bi-house fs-1"></i>
          </a>
          <ul
            class="
              d-block
              p-3
              mx-auto
              nav-pills nav-flush
              flex-row flex-nowrap
              mb-auto
              align-items-center
            "
            style="list-style-type: none"
          >
            <li class="nav-item">
              <a
                href="#"
                class="nav-link py-3 px-2 text-white"
                title=""
                data-bs-toggle="tooltip"
                data-bs-placement="right"
                data-bs-original-title="Home"
              >
                <i class="bi bi-file-bar-graph fs-1"></i>
              </a>
            </li>
            <li>
              <a
                href="#"
                class="nav-link py-3 px-2 text-white"
                title=""
                data-bs-toggle="tooltip"
                data-bs-placement="right"
                data-bs-original-title="Dashboard"
              >
                <i class="bi-speedometer2 fs-1"></i>
              </a>
            </li>
            <li>
              <a
                href="#"
                class="nav-link py-3 px-2 text-white"
                title=""
                data-bs-toggle="tooltip"
                data-bs-placement="right"
                data-bs-original-title="Orders"
              >
                <i class="bi-table fs-1"></i>
              </a>
            </li>
            <li>
              <a
                href="#"
                class="nav-link py-3 px-2 text-white"
                title=""
                data-bs-toggle="tooltip"
                data-bs-placement="right"
                data-bs-original-title="Products"
              >
                <i class="bi-heart fs-1"></i>
              </a>
            </li>
            <li>
              <a
                href="#"
                class="nav-link py-3 px-2 text-white"
                title=""
                data-bs-toggle="tooltip"
                data-bs-placement="right"
                data-bs-original-title="Customers"
              >
                <i class="bi-people fs-1"></i>
              </a>
            </li>
            <li>
              <a
                href="#"
                class="nav-link py-3 px-2 text-white"
                title=""
                data-bs-toggle="tooltip"
                data-bs-placement="right"
                data-bs-original-title="Customers"
              >
                <i class="bi bi-gear fs-1"></i>
              </a>
            </li>
          </ul>
          <div class="dropdown">
            <a
              href="#"
              class="
                d-flex
                align-items-center
                justify-content-center
                p-3
                text-white text-decoration-none
                dropdown-toggle
              "
              id="dropdownUser3"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              <i class="bi-person-circle fs-1"></i>
            </a>
            <ul
              class="dropdown-menu text-small shadow"
              aria-labelledby="dropdownUser3"
            >
              <li><a class="dropdown-item" href="#">New project...</a></li>
              <li><a class="dropdown-item" href="#">Settings</a></li>
              <li><a class="dropdown-item" href="#">Profile</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
// Graph
</script>


<style scoped>
.sidbar .active {
  border-radius: 5px;
  box-shadow: 0 2px 5px 0 rgb(0 0 0 / 16%), 0 2px 10px 0 rgb(0 0 0 / 12%);
}

/*.sidebar-sticky {
  position: relative;
  top: 0;
  height: calc(100vh - 48px);
  padding-top: 0.5rem;
  overflow-x: hidden;
  overflow-y: auto; /* Scrollable contents if viewport is shorter than content. */
/*}
/*h3 {
  margin-top: 10px;
}*/
</style>