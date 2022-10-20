<template>
  <div class="container-fluid">
    <div class="row flex-nowrap">
      <div class="col-auto col-md-3 col-xl-2 px-0">
        <div
          class="
            d-flex
            flex-column
            align-items-start align-items-sm-start
            px-4
            pt-2
            text-white
          "
          style="
            background-color: #f2f2fd;
            border-radius: 25px;
            margin-top: 2rem;
            left: 99rem;
            top: 3rem;
            width: max-content;
          "
        >
          <a
            href="/"
            class="
              d-flex
              justify-content-end
              align-items-end
              pb-3
              mb-md-0
              me-md-auto
              text-dark text-decoration-none
            "
          >
            <div class="list-group list-group-flush">
              <ul class="navbar-nav m-auto d-flex flex-row justify-content-end">
                <li class="nav-item">
                  <a class="nav-link me-lg-0" href="#">
                    <h3 class="bi bi-calendar-date me-4"></h3>
                  </a>
                </li>

                <li class="nav-item me-lg-0">
                  <a class="nav-link" href="#">
                    <h3 class="bi bi-bell me-4"></h3>
                  </a>
                </li>
                <li class="nav-item me-2 me-lg-0">
                  <a class="nav-link" href="#">
                    <h3 class="bi bi-chat-left-dots me-3"></h3>
                  </a>
                </li>
                <!-- Avatar -->
                <li class="nav-item dropdown">
                  <a
                    class="
                      nav-link
                      dropdown-toggle
                      hidden-arrow
                      d-flex
                      align-items-center
                    "
                    href="#"
                    id="navbarDropdownMenuLink"
                    role="button"
                    data-bs-toggle="dropdown"
                  >
                    <img
                      src="https://mdbootstrap.com/img/Photos/Avatars/img (31).jpg"
                      class="rounded-circle"
                      height="33"
                      alt=""
                      loading="lazy"
                    />
                  </a>
                  <ul class="dropdown-menu dropdown-menu-end">
                    <li><a class="dropdown-item" href="#">My profile</a></li>
                    <li><a class="dropdown-item" href="#">Settings</a></li>
                    <li><a class="dropdown-item" href="#">Logout</a></li>
                  </ul>
                </li>
              </ul>
            </div>
          </a>

          <hr />
          <div class="todo list-group list-group-flush p-3 my-4 text-dark">
            <h3 class="fw-bold text-start m-2">Your to-Do List</h3>

            <!--1-->
            <div class="row">
              <div class="mb-2">
                <div
                  class="card"
                  style="background-color: #f2f2fd; border: none"
                >
                  <div class="card-body">
                    <div class="d-flex justify-content-between px-md-1">
                      <div class="align-self-center">
                        <span
                          class="rounded-pill p-4 align-items-center me-2"
                          style="background-color: #e3e5f5"
                          ><i class="bi bi-calendar-range me-2 p-2 fs-3"></i
                        ></span>
                      </div>
                      <div class="text-end">
                        <h4>Run payroll</h4>
                        <p class="mb-0 text-muted">Mar 4 at 6:00</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!--2-->
            <div class="row">
              <div class="mb-2">
                <div
                  class="card"
                  style="background-color: #f2f2fd; border: none"
                >
                  <div class="card-body">
                    <div class="d-flex justify-content-between px-md-1">
                      <div class="align-self-center">
                        <span
                          class="rounded-pill p-4 align-items-center me-4"
                          style="background-color: #e3e5f5"
                          ><i class="bi bi-calendar-range me-2 p-2 fs-3"></i
                        ></span>
                      </div>
                      <div class="text-end">
                        <h4>Run payroll</h4>
                        <p class="mb-0 text-muted">Mar 4 at 6:00</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!--3-->
            <div class="row">
              <div class="mb-2">
                <div
                  class="card"
                  style="background-color: #f2f2fd; border: none"
                >
                  <div class="card-body">
                    <div class="d-flex justify-content-between px-md-1">
                      <div class="align-self-center">
                        <span
                          class="rounded-pill p-4 align-items-center me-4"
                          style="background-color: #e3e5f5"
                          ><i class="bi bi-calendar-range me-2 p-2 fs-4"></i
                        ></span>
                      </div>
                      <div class="text-end">
                        <h4>Run payroll</h4>
                        <p class="mb-0 text-muted">Mar 4 at 6:00</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!--4-->
            <div class="row">
              <div class="mb-2">
                <div
                  class="card"
                  style="background-color: #f2f2fd; border: none"
                >
                  <div class="card-body">
                    <div class="d-flex justify-content-between px-md-1">
                      <div class="align-self-center">
                        <span
                          class="rounded-pill p-4 align-items-center me-4"
                          style="background-color: #e3e5f5"
                          ><i class="bi bi-calendar-range me-2 p-2 fs-3"></i
                        ></span>
                      </div>
                      <div class="text-end">
                        <h4>Run payroll</h4>
                        <p class="mb-0 text-muted">Mar 4 at 6:00</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card my-3 p-3 rounded-5 border border-0 text-dark">
            <div class="card-body">
              <div class="d-flex justify-content-between px-md-1">
                <div class="align-self-center">
                  <li class="fs-1" style="color: #6e6af8"></li>
                </div>
                <div class="text-start">
                  <h3 class="text-bold">Board Meetingh</h3>
                  <p class="mb-0">Feb 22 at 6:00 PM</p>
                  <p class="mb-0 text-muted">
                    we have been invited to attend a meetingof<br />
                    the board Diraction
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
