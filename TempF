<?
// Los de Path Traversal problemen in deze applicatie op 

    $pagedir = "pages";

    if (!isset($_GET['page'])) {
        header("Location: ?page=welkom");
        exit;
    }

    $page = $_GET['page'];

    if (file_exists("$pagedir/$page")) {
        print file_get_contents("$pagedir/$page");
    }
