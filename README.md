# My_Updates
#2024/01/28 - Tuesday
----------------------
#Today my task , "Organise and display videos by category using an accordion-style layout"
i try to solve the this problem using  Foreach loop in laravel, task done but have issue, Foreach loop is not good solution this problem, so best solution is use the Laravel Eloqunt.
#
@foreach ($categories as $category)
    #<div class="category-section">
        #<h4 class="category-name">{{ $category->name }}</h4>
        #<div class="row mx-1">
            #@foreach ($lmsVideoCategories as $lvc)
               #@if ($lvc->lms_category_id == $category->id)
                   # @foreach ($video_list as $video)
                       # @if ($video->id == $lvc->video_id)
                        @endif
                    @endforeach
                @endif
            @endforeach
        </div>
    </div>
@endforeach
