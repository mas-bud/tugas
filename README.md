<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="style/style.css">
    <title>BLLio</title>
</head>

<body>
    <!-- navbar -->
    <nav class="navbar fixed-top navbar-expand-lg navbar-light" style="background-color:lightgray">
        <div class="container">
            <img src="img/logo.jpeg.jpg" height="30">
            <a class="navbar-brand font-weight-bold" href="#">BLLio</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ml-auto mr-4">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Beranda <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Reseller <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Hubungi kami <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Bantuan <span class="sr-only">(current)</span></a>
                    </li>
                </ul>
                <form class="form-inline my-2 my-lg-0">
                    <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>
    <!-- akhir navbar -->

    <!-- pembagian kolom -->
    <div class="row mt-5 no-gutters">
        <div class="col-md-2 bg-light" style="background-color: bisque;">
            <div class="list-group list-group-flush p-1 pt-3">
                <a href="#" class="list-group-item list-group-item-action active font-weight-bold">KATEGORI PRODUK</a>
                <a href="#" class="list-group-item list-group-item-action">Peralatan Elektronik</a>
                <a href="#" class="list-group-item list-group-item-action">Sparepart</a>
                <a href="#" class="list-group-item list-group-item-action">Fashion Pria</a>
                <a href="#" class="list-group-item list-group-item-action">Fashion Wanita</a>
                <a href="#" class="list-group-item list-group-item-action">Peralatan Rumah Tangga</a>
            </div>
        </div>
        <div class="col-md-10">
            <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="img/carousel/carousel1.jpg" class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                        <img src="img/carousel/carousel2.jpg" class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                        <img src="img/carousel/carousel3.jpg" class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                        <img src="img/carousel/carousel4.jpg" class="d-block w-100">
                    </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>
            <!-- produk -->
            <h4 class="text-center font-weight-bold m-4">PRODUK KAMI</h4>
            <!-- baris produk 1 -->
            <div class="row mx-auto">
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk1.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 1</h5>
                        <p class="card-text">Keterangan produk 1</p>
                        <a href="#" class="btn btn-primary" data-target="#produk1" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk2.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 2</h5>
                        <p class="card-text">Keterangan produk 2</p>
                        <a href="#" class="btn btn-primary" data-target="#produk2" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk3.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 3</h5>
                        <p class="card-text">Keterangan produk 3</p>
                        <a href="#" class="btn btn-primary" data-target="#produk3" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk4.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 4</h5>
                        <p class="card-text">Keterangan produk 4</p>
                        <a href="#" class="btn btn-primary" data-target="#produk4" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
            </div>
            <!-- baris produk 2 -->
            <div class="row mx-auto mt-5">
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk5.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 5</h5>
                        <p class="card-text">Keterangan produk 5</p>
                        <a href="#" class="btn btn-primary" data-target="#produk5" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk6.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 6</h5>
                        <p class="card-text">Keterangan produk 6</p>
                        <a href="#" class="btn btn-primary" data-target="#produk6" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk7.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 7</h5>
                        <p class="card-text">Keterangan produk 7</p>
                        <a href="#" class="btn btn-primary" data-target="#produk7" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
                <div class="card mr-2 ml-2" style="width: 14rem;">
                    <img src="img/produk/produk8.jpeg" class="card-img-top">
                    <div class="card-body bg-light">
                        <h5 class="card-title">produk 8</h5>
                        <p class="card-text">Keterangan produk 8</p>
                        <a href="#" class="btn btn-primary" data-target="#produk8" data-toggle="modal">Detail</a>
                        <a href="#" class="btn btn-primary">Beli</a>
                    </div>
                </div>
            </div>
            <!-- pop up detail -->
            <div class="modal fade" id="produk1" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk1.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 1 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 3000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- produk 2 -->
            <div class="modal fade" id="produk2" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk2.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 2 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 5000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- produk 3 -->
            <div class="modal fade" id="produk3" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk3.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 3 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 6000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- produk 4 -->
            <div class="modal fade" id="produk4" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk4.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 4 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 5000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- produk 5 -->
            <div class="modal fade" id="produk5" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk5.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 5 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 10000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- produk 6 -->
            <div class="modal fade" id="produk6" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk6.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 6 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 15000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- produk 7 -->
            <div class="modal fade" id="produk7" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk7.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 7 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 5000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- produk 8 -->
            <div class="modal fade" id="produk8" tabindex="-1" role="dialog" aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Detail Produk</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
            </button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 ">
                                    <img src="img/produk/produk8.jpeg" width="200px">
                                </div>
                                <div class="col-md-6 ">
                                    <table class="table table-borderless">
                                        <tr>
                                            <th>Nama Produk</th>
                                            <td>Produk 1 adalah apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Merk/Type</th>
                                            <td>Merknya apa?</td>
                                        </tr>
                                        <tr>
                                            <th>Harga</th>
                                            <td>Rp. 5000</td>
                                        </tr>
                                        <tr>
                                            <th>Garansi</th>
                                            <td>Ada garansi gak?</td>
                                        </tr>
                                        <tr>
                                            <th>Stok Produk</th>
                                            <td>Ada stoknya?</td>
                                        </tr>
                                    </table>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-primary" data-dismiss="modal">Kembali</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- akhir pop up detail -->
        </div>
    </div>
    <!-- akhir pembagian kolom -->

    <!-- footer -->
    <footer class="bg-dark text-white">
        <h5 class="text-center font-weight-bold m-4">Copyright 2019 | pemrograman web</h5>
    </footer>
    <!-- akhir footer -->

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>


</body>

</html>
