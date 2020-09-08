# hello-world
the first repository
@GetMapping("/search/{keyword}")
	public @ResponseBody
	List<LibraryBook> searchAll(@PathVariable String keyword){
		return libraryBookService.searchBookByName(keyword);
	}
