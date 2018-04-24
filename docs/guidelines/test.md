# Guideline


<!--
<link rel="stylesheet" href="/css/bootstrap-iso.css">
<link rel="stylesheet" href="/css/ez-guidelines.css">
-->

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>






<div class="bootstrap-iso">


test bootstrap

<br>

<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>


<br />

<div class="btn-group">
  <button type="button" class="btn btn-danger dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Action
  </button>
  <div class="dropdown-menu">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item" href="#">Separated link</a>
  </div>
</div>

<br />

<span class="badge badge-pill badge-primary">Primary</span>
<span class="badge badge-pill badge-secondary">Secondary</span>
<span class="badge badge-pill badge-success">Success</span>
<span class="badge badge-pill badge-danger">Danger</span>
<span class="badge badge-pill badge-warning">Warning</span>
<span class="badge badge-pill badge-info">Info</span>
<span class="badge badge-pill badge-light">Light</span>
<span class="badge badge-pill badge-dark">Dark</span>

<br><br><br>



<div class="ez-guidelines">

test ez:
<br>


button:
<button type="button" class="ez-button ez-button-primary">Confirm selection</button>

<br>
<br>
<br>

<button type="button" class="ez-button ez-button-ghost">Show 10 more results</button>



<br>
<br>
<br>

<button type="button" class="ez-button ez-button-primary"><span class="ez-icon-relations"></span>Select content</button>


<br>
<br>
<br>


<button class="ez-action ez-action-discoverybar">
	<p class="ez-action-iconwrapper"><span class="ez-icon-search ez-action-icon"></span></p>
	<p class="ez-action-label">Search</p>
</button>





<h4 class="u-move-down-xlarge">Default table with checkboxes and interaction</h4>
<hr>
<div class="flex-wrapper">
    <div class="ez-table ez-table-checkboxes">
        <div class="table-title">
            <p>Content type groups</p>
            <div class="container-buttons">
                <button type="button" class="ez-button ez-button-secondary"><span class="ez-icon-create"></span>Add group</button>
                <button type="button" class="ez-button ez-button-negative" disabled="disabled"><span class="ez-icon-trash"></span>Delete</button>
            </div>
        </div>
        <div class="table-container">
            <table>
                <tr>
                    <th></th>
                    <th>Name</th>
                    <th>Id</th>
                    <th></th>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cba" type="checkbox" name="checkbox">
                            <label for="cba" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">Content</a></td>
                    <td>1</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cbb" type="checkbox" name="checkbox">
                            <label for="cbb" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">Users</a></td>
                    <td>2</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cbc" type="checkbox" name="checkbox">
                            <label for="cbc" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">Media</a></td>
                    <td>3</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cb4" type="checkbox" name="checkbox">
                            <label for="cb4" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">More content</a></td>
                    <td>4</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cb5" type="checkbox" name="checkbox">
                            <label for="cb5" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">More users</a></td>
                    <td>5</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cb6" type="checkbox" name="checkbox">
                            <label for="cb6" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">More media</a></td>
                    <td>6</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cb7" type="checkbox" name="checkbox">
                            <label for="cb7" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">More content 2</a></td>
                    <td>7</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cb8" type="checkbox" name="checkbox">
                            <label for="cb8" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">More users 2</a></td>
                    <td>8</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div class="ez-form-clickable">
                            <input id="cb9" type="checkbox" name="checkbox">
                            <label for="cb9" class=""></label>
                        </div>
                    </td>
                    <td><a href="#">More media 2</a></td>
                    <td>9</td>
                    <td>
                        <a href="#" class="table-iconbutton">
                            <div class="table-iconbutton-edit">
                                <span class="ez-icon-edit"></span>
                            </div>
                        </a>
                    </td>
                </tr>
            </table>
        </div>
    </div>
</div>






</div>
