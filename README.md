# Assignment 6
class Media{
  constructor(title, artistOrDirector, duration, rating){
    this.title = title
    this.duration = duration
    this.artist = artistOrDirector
    this.director = artistOrDirector
    this.rating = rating

    var counter;
    var playlist = []
  }
  playlist(){
    playlist.push(Media)

    return playlist

    console.log(playlist)
  }

  nextSong(){
  var counter;
    console.log(playlist[counter]);
    counter++;
    if(counter>playlist.length){
      counter = 0
      return counter
    } else {
      return counter
    }
  }

    playing(song){
      if this.title = playlist.title[counter]{
      console.log(True)
    } else {
      console.log(False)
    }

    sortPlaylist(){
      playlist.sort();
      console.log(playlist);
    }
}

let TheDarkKnight = new Media ("The Dark Knight", "Christopher Nolan", "2:32", "5 stars")
console.log(TheDarkKnight.director)
console.log(TheDarkKnight.playlist)

let OneWeek = new Media ("OneWeek", "BareNakedLadies", "2:54")
console.log(OneWeek.title)
console.log(OneWeek.duration)
console.log(OneWeek.artist)

console.log(OneWeek.playlist)
console.log(OneWeek.NextSong)
